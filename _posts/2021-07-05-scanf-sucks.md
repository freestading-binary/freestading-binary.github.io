---
layout: post
title: Scanf sucks
description: every kind of shit you've ever seen
categories: narcotics anonymous, drunks, anarchism, your mom
---

# Scanf sucks!

well, you probably scanf daily in your C code, this is notable when we venture into the C language and come across user input, formally known as input. The point is, the way the most popular input function (scanf) was created, it's basically a bazooka shot in the middle of an ant in the desert, we'll discuss a little bit below.

Let's create a character from now on, his name will be Josh. Josh is a kid who likes the C language, and with that he's been practicing. Josh needs to create a simple program, just ask the user's age and then the value is returned to the screen. Well then, this would be something very simple to create.

It could be created as follows:

{% highlight ruby %}
#include <stdio.h>

int main()
{
	int age;
	printf("\nWhats your age? ");
	scanf("%d", &age);

	printf("\n%d", age);

	return 0;
}

{% endhighlight %}

See how simple though, what if I told you there are problems using the scanf function? Our dear Josh would probably be heartbroken. However, let's teach you why...