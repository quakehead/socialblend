
Web page: http://quakehead.github.io/socialblend








## Feautures


- functions
	- hashtag(s) -> list of posts
	- category -> list of posts



## Twitter api


* console https://dev.twitter.com/console


* [rest api](https://dev.twitter.com/docs/api/1.1)


* search api
		https://dev.twitter.com/docs/using-search
		
	- complete ref
		https://dev.twitter.com/docs/api/1.1/get/search/tweets


* base url:
	https://api.twitter.com/1.1/search/tweets.json

e.g:
	https://api.twitter.com/1.1/search/tweets.json?q=%23dogs&src=typd

### Getting a token and authenticating

- tutorial
	http://beautifulbytes.wordpress.com/2013/06/18/oauth2-with-angularjs-to-access-twitter/


* How to use on twitter api docs
	https://dev.twitter.com/docs/auth/application-only-auth


- token for web api:
	https://dev.twitter.com/docs/auth/tokens-devtwittercom

* keys:
	https://apps.twitter.com/app/5783716/keys





	

### Getting a list of posts



### Embedding





## Instagram api


access_token=1077730514.1fb234f.d79420046077461ba15d089825b12b56


* Queries:


- cats
	https://api.instagram.com/v1/tags/cats/media/recent?q=cats&count=10&access_token=1077730514.1fb234f.d79420046077461ba15d089825b12b56


- https://api.instagram.com/v1/tags/search?q=snowy&access_token=

- https://api.instagram.com/v1/tags/cats/media/recent?q=cats&count=10&access_token=1077730514.1fb234f.d79420046077461ba15d089825b12b56

- Popular Media: https://api.instagram.com/v1/media/popular?access_token=1077730514.1fb234f.d79420046077461ba15d089825b12b56 



### Getting a list

### Embedding



## Imgur



https://api.imgur.com/3/gallery/r/funny/top/0




## HTML codes

- #	%23
- @ %40


			<ul>
				<!-- TODO change class -->
				<div class="instagram" ng-repeat="post in posts">
					<a href="{{post.url}}"><img width="306" height="306" ng-show="post.pic" ng-src="{{post.pic}}"></a>
					{{post.text}}
				</div>
			</ul>
			






