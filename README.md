# Media Queries Example Code

This is example code that belongs to a lesson about responsive webdesign using flexbox and media queries. Also note how the css rules are organized into several sections, like _nav and _brands. The sole purpose of index.css is to connect them. This is in accordance with basic programming principles like separation of concerns and encapsulation. CSS doesn't provide this functionality out of the box so we have to create it ourselves by sticking to certain naming conventions. We are encapsulating all css style rules that belong to `class=brands` by prepending them with .brands. If you want to know more about methods to structure your css code check out:

    *   http://getbem.com/introduction/
    *   http://smacss.com/

Later in the course we are going to use something called SASS, with which we don't have to prepend everything with a class name in such an ugly manner. Remember: repitition is bad too! In this case however repitition is a necessary evil to prevent the much bigger vice of dumping all your css rules in 1 giant file without encapsulating them.