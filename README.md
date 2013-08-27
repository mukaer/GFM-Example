GFM-Example
===========

GitHub Flavored Markdown Example


Index
---
* source

~~~
 This is head1
 =============

 This is head 2
 --------------
~~~

* result

This is head1
=============

This is head 2
--------------

table (PHP-Markdown style)
---

* source

~~~
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
~~~

* result

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell


* source

~~~
| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |
~~~

* result

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |


code
---

* source


    ```
    this is code block
    ```


* result

```
this is code block
```


* source


    ```ruby
    get '/' do
      "Hello world "
    end
    ```


* result

```ruby
get '/' do
  "Hello world "
end
```


autolink
--------

* source

```
http://mukaer.com
```

* result

http://mukaer.com



strikethrough
-------------

* source

```
this is ~~good~~ bad
```

* result

this is ~~good~~ bad


Index
---
* source
* result
