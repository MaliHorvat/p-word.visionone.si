all:
	sh render_template Dockerfile.j2 '{"base": "debian"}' > Dockerfile.debian
	sh render_template Dockerfile.j2 '{"base": "alpine"}' > Dockerfile.alpine
.PHONY: all
