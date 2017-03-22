# Installation
1. Clone or download repository
2. Install Docker
3. Open terminal and go to repository
4. Run the following command:
	```
	sudo docker run --rm --label=jekyll --volume="$(pwd)":/srv/jekyll -it -p 127.0.0.1:4000:4000 jekyll/jekyll bundle exec jekyll serve
	```
5. Open http://127.0.0.1:4000/ in your browser to view web locally
