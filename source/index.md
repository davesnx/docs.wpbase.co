---
title: docs.wpbase.co | Documentation

language_tabs:
  - shell

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='http://github.com/tripit/slate'>Follow @wpbase</a>

includes:
  - errors

search: false
---

# Introduction

Welcome to the documentation of **api.wpbase.co**

I'm currently developing the API and I want to make it simple and usefull for all wordpress developers.

<aside class="warning">
<!-- Añadir logo slack -->
If you want to give feedback/help/love about the project you can join the <a href="#">Slack</a> or <a href="#">discuss.wpbase.co</a>
</aside>

## What is wpbase?

**wpbase** is a API for create WordPress Skeletons as a service. With only a request you can build a instalation of WordPress with what <a href="#plugins">plugins</a> you want and also <a href="#themes">themes</a>, and soon... <a href="#configs">configs</a>, you can choose the version, etc..

Soon you will can do:
<ul>
<li>Upload via FTP to a Server</li>
<li>Choose user/password of wp-admin</li>
<li>Set up the Post Types</li>
<li>etc...</li>
</ul>

This API are made for developers, if you aren't or just want to try it. I create <a href="http://wpbase.com">wpbase.com</a> for doing the same job in a easy way. 

## Getting started

# Authentication

<span class="endpoint post">/build</span>

> To authorize, use this code:

```shell
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```

> Make sure to replace `meowmeowmeow` with your API key.

The uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).</p>

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

# Build

<span class="endpoint get">/build</span>

The uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).</p>

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

<span class="endpoint post">/build</span>

The uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).</p>

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:


# Plugins

## Get all Plugins
## Get one Plugin
## Update one Plugin
## Delete one Plugin

# Themes

## Get all Themes
## Get one Theme
## Update one Theme
## Delete one Theme

# Configs

<aside class="notice">This error section is stored in a separate file in `includes/_errors.md`. Slate allows you to optionally separate out your docs into many files...just save them to the `includes` folder and add them to the top of your `index.md`'s frontmatter. Files are included in the order listed.</aside>

## Get all Configs
## Get one Config
## Update one Config
## Delete one Config
