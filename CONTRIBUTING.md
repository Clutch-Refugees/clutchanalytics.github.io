# Contributing

## Add yourself to authors list

Please add yourself to the authors list in [_config.yml](https://github.com/clutchanalytics/clutchanalytics.github.io/blob/master/_config.yml)

You can enter the following details:

* **name**: Your display name.

* **gravatar**: Your [Gravatar](http://gravatar.com) hash. If `test@example.com` if your email address, you can generate your Gravatar hash by running `echo -n "test@example.com" | md5` in your terminal. We'll then use the Gravatar next to your name in the blog posts. You can change your avatar anytime without disturbing the blog :)

* **github**: If you have a GitHub account, enter your username, and we'll link to your profile.

* **twitter**: If you have a twitter account, enter your username, and we'll link to your profile. This is used only if your GitHub username isn't specified.


### Example: Adding "John Doe" to authors list and using detail in blog post

For *"John Doe"*, let's use the username *johndoe*. To add `johndoe` to the authors list...

```
authors:
  johndoe:
    name: John Doe
    gravatar: 55502f40dc8b7c769880b10874abc9d0
    twitter: JohnDoe
    github: JohnDoe
```

**Note:** The author's username is case sensitive.

Now to refer to the author in the blog post, use `author: johndoe` in the YAML frontmatter of the blog post. Everything else will be taken care of.
