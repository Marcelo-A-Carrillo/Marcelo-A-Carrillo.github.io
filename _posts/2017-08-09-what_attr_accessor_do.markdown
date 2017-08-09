---
layout: post
title:  "What attr_accessor do?"
date:   2017-08-09 12:51:48 -0400
---


To understand attr_accesor first lets create a class.

We are going to create a class by typing:

```
Class Doggy

end
```

Now that we have created a class we are going to create an attr_accessor inside of the class

```
Class Doggy
attr_accessor
end
```

What attr accessor do it gives it attribute to build with your object. In other words attr_accessor allows you to build objects with attributes.

to write attr_accessor you used : follow by the name of the attribute. For example


```
Class Doggy
attr_accessor :age 
end
```

If you want to add more than attribute you can do that by adding a comma after each attribute. For exmple:

```
Class Doggy
attr_accessor :age, :name, :genre 
end
```

 Hope this simple explanation will help you understand what attr_accessor do




