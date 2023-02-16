all:
	docker build -t kaityo256/gs_sample .

no-cache:
	docker build -t kaityo256/gs_sample . --no-cache

run:
	docker run -it -e DISPLAY=$$(hostname):0 -v ~/.Xauthority:/root/.Xauthority kaityo256/gs_sample
