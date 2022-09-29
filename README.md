# starting_my_online_store

<h1>Complete project</h1>

<lo>
<li> creation of a product catalog; </li>
<li> implementation of a shopping cart using Django sessions;  </li>
<li> creation of custom context handlers;  </li>
<li> customer order management; </li>
<li> configuration of Celery in the project using RabbitMQ as a message broker;  </li>
<li> sending asynchronous notifications to customers using Celery;  </li>
<li> Celery monitoring using Flower. </li>

<p>// Windows compatible version cannot be above 4+</p>

<li>**Install celery</li>

<li>pip install celery==4.4.7</li>

<li>**Open the project in the control panel</li>
<li>open virtual environment</li>

<li>pip install celery==4.4.7</li>

<li>**Celery needs gevent to work properly.</li>

<li>pip install manager</li>

<li>*Activate celery together with gevent</li>

<li>celery -A myshop worker -l info -P gevent</li>

<li>// SECOND PART OF THE PROJECT</li>

<li>• integrate a payment gateway into our project;</li>
<li>• export orders to CSV files;</li>
<li>• create custom views for the administration site;</li>
<li>• dynamically generate PDF invoices.</li>

<p>//Braintree provides an API that allows you to process online payments with various payment methods such as credit card, PayPal, Google Pay and Apple Pay. Learn more about Braintree at https://www.braintreepayments.com/.</p>
</lo>
