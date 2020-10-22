# Short Answer Questions

TAEHYEOK LEE Luke
A01075902
midterm for 1620 October 2020
BCIT

## Q1 Explain what Git and GitHub are. How are they different?
Git is a version control system that can manage and track source code records.
GitHub is a cloud-based hosting service that can manage Git repositories.
The difference between Git and GitHub is that Git is an open source tool developer that installs locally to manage source code, and GitHub is an online service that allows developers using Git to connect, upload or download resources.

## Q2 What is a 'Branch' in Git? How could you create a new branch and what would you commonly use a branch for?
Git's branch is simply a light movable pointer to one of these commits. It can be created using the command " git branch branch_name " and can be developed independently from the original.

## Q3 What is the http status code you get when a resource is not found? What category of status code does this belong to (other status codes that start with the same number)? Does this status code indicate if the representation is permanent?
Http Status code is "404 Not Found". It's in the Client error responses category. It is not indicate whether the resource is temporarily or permanently missing.

## Q4 What is not correct about styling of the given h2 element in the code below? Which color will the h2 be and why?
Need to use '.' before <class> in <head>.
It will be red color.

## Q5 List and briefly describe the parts of a URL
Protocol: It indicates which protocol the browser must use.
Domain Name: It indicates which Web server is being equested. Port:  It indicates the technical "gate" used to access the resources on the web server.
Path to the file: It is the path to the resource on the Web server.
Parameters: The Web server can use those parameters to do extra stuff before returning the resource to the user.
Anchor: to another part of the resource itself.

## Q6 What is an http header? Provide examples of three http header fields and briefly describe what each does
HTTP headers allow clients and servers to forward additional information in HTTP requests or responses.
1. Accept: The Accept request-header field can be used to specify certain media types which are acceptable for the response.
2. Cache-Control: The Cache-Control general-header field is used to specify directives that MUST be obeyed by all caching mechanisms along the request/response chain.
3. Expires: The Expires entity-header field gives the date/time after which the response is considered stale.

## Q7 Describe the CSS box model? From inside to outside what are the different parts of the box model?
CSS box model is used when talking about design and layout.
Content - The content of the box, where text and images appear
Padding - Clears an area around the content
Border - A border that goes around the padding and content
Margin - Clears an area outside the border.

## Q8 Briefly describe the 4 CSS Combinator selectors that we looked at in class. Provide an example of each.
Child Combinator(>): The child selector selects all elements that are the children of a specified element.
ex. div > p {
  background-color: yellow;
}
descendant Combinator(space): The descendant selector matches all elements that are descendants of a specified element.
ex. div p {
  background-color: yellow;
}
Adjacent Sibling Combinators(+): The adjacent sibling selector selects all elements that are the adjacent siblings of a specified element.
ex. div + p {
  background-color: yellow;
}
General Sibling Combinator(~): The general sibling selector selects all elements that are siblings of a specified element.
ex. div ~ p {
  background-color: yellow;
}

## Q9 Will these two paragraphs appear on two separate lines? Why?
Yes. Because It divided by <p>

## Q10 Identify and explain two of the errors that exist in the code snippet below.
```
{
<img src="images/cat.png">
==> <img src="/images/cat.png">
<a href="https://bcit.ca">bcit site< title="bcit" /a>
==> <a href="https://bcit.ca" title="bcit">bcit site</a>
}
```
