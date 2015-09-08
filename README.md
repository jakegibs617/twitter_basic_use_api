Step 1 $touch .gitignore fill with: keys.rb

Step 2 $touch keys.rb
  in keys.rb file
	  ```
		def consumer_key
		  OAuth::Consumer.new(
		    "consumer key chars",
		    "secret consumer key chars")
		end
		def access_token
		  OAuth::Token.new(
		  "access token chars",
		  "secret access token chars")
		end
		 ```
Step 3 $ruby server.rb
Step 4 visit localhost4567/
