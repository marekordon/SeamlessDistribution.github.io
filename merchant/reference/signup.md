---
layout: default
title: SEQR Integration Sign up
description: SEQR Integration Sign up
---

# Get login credentials

You need to [contact](/contact) Seamless to get reseller ID and password. With these you call the registerTerminal API request to receive a terminal ID. The terminal ID and password can then be used to make payment requests.


#SEQR test credentials

Example terminal context, that can be used before contacting us:
{% highlight python %}
context.initiatorPrincipalId.type = 'TERMINALID'
context.initiatorPrincipalId.id = 'test_terminal_do_not_unregister'
context.password = '12345678'
{% endhighlight %}

Example shop/reseller context, that can be used before contacting us:
{% highlight python %}
context.initiatorPrincipalId.type = 'RESELLERUSER'
context.initiatorPrincipalId.id = 'public_test_shop'
context.initiatorPrincipalId.userId = '9900'
context.password = '1234'
{% endhighlight %}

#eProducts test credentials

{% highlight python %}
context.clientId = 'samplereseller'
context.clientUserId = '9900'
context.password = '12345678'
{% endhighlight %}





