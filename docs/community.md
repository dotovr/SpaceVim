---
title:  "Community"
---

# Community

Try these SpaceVim hangouts for any questions, problems or comments. 

## Ask
- [issue tracker](https://github.com/SpaceVim/SpaceVim/issues) for issue and feature requests
- vi StackExchange for "how to" & configuration questions
- [Twitter](https://twitter.com/SpaceVim) for hugs & pithy comments

## Chat
- [![Gitter](https://badges.gitter.im/SpaceVim/SpaceVim.svg)](https://gitter.im/SpaceVim/SpaceVim?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
- [![QQ](https://img.shields.io/badge/QQ群-121056965-blue.svg)](https://jq.qq.com/?_wv=1027&k=43DB6SG)
- [![Facebook](https://img.shields.io/badge/FaceBook-SpaceVim-blue.svg)](https://www.facebook.com/SpaceVim)

## Discuss

To report an issue or give feedback to the developers, please use the [issue tracker](https://github.com/SpaceVim/SpaceVim/issues). 

## Blogs

<ul>
    {% for post in site.posts %}
        {% if post.categories contains "changelog" %}
        {% else %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
        {% endif %}
    {% endfor %}
</ul>
