```go
package main

import "fmt"

type Coder struct {
	name, pronouns, twitter, email, blog, location, title 	string
	techStack, hobbies                             		[]string
	openToOpportunities                            		bool
}

func main() {

	var joe = Coder{
		name:                "joseph",
		title:		     "plant dad",
		pronouns:            "he/him",
		email:               "jsphwllng@gmail.com",
		techStack:           []string{"ruby", "python", "javascript", "html & css", 
					"mongoDB", "postgreSQL", "rails", "react", "go",
					"heroku", "AWS", "MERN", "RESTful APIs"},
		twitter:             "@jsphwllng",
		hobbies:             []string{"ping pong", "brewing", "yoga"},
		blog:                "https://dev.to/jsphwllng",
		location:            "berlin",
		openToOpportunities: true,
	}

	fmt.Printf("%+v\n", joe)
}
```
