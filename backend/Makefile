build:
	GOOS=linux go build -o app
	docker build -t gcr.io/my-college-proje-1480531728089/say .
	rm -f app

push:
	gcloud docker -- push gcr.io/my-college-proje-1480531728089/say