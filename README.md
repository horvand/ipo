# IPO
Input Processing Output

based on the [IPO](http://en.wikipedia.org/wiki/IPO_Model) pattern. 
With the added benefit of having a buffer layer between in, process and output.
The buffers will be utilizing the (amqp)[https://www.amqp.org/] using [rabbitmq](http://www.rabbitmq.com)/a.

There are 5 nodes:

in -> proc_buff -> proc -> out_buff -> out
