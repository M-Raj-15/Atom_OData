SOAP VS REST
KEY DIFFERENCE
SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State Transfer.
SOAP is a protocol whereas REST is an architectural pattern.
SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.
SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.
Comparing SOAP vs REST API, SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.
SOAP cannot make use of REST whereas REST can make use of SOAP.

REST:
REST stands for Representational State Transfer
REST is an Architectural style in which a web service can only be treated as a RESTful service if it follows the constraints of being
Client Server
Stateless
Cacheable
Layered System
Uniform Interface
REST can make use of SOAP as the underlying protocol for web services, because in the end it is just an architectural pattern.
REST use Uniform Service locators to access to the components on the hardware device. For example, if there is an object which represents the data of an employee hosted on a URL as  the below are some of URI that can exist to access them.
REST does not need much bandwidth when requests are sent to the server. REST messages mostly just consist of JSON messages. Below is an example of a JSON message passed to a web server. You can see that the size of the message is comparatively smaller to SOAP.
REST permits different data format such as Plain text, HTML, XML, JSON, etc. But the most preferred format for transferring data is JSON.

SOAP SOAP stands for Simple Object Access Protocol

SOAP is a protocol. SOAP was designed with a specification. It includes a WSDL file which has the required information on what the web service does in addition to the location of the web service.

SOAP cannot make use of REST since SOAP is a protocol and REST is an architectural pattern.

SOAP uses service interfaces to expose its functionality to client applications. In SOAP, the WSDL file provides the client with the necessary information which can be used to understand what services the web service can offer.

SOAP can only work with XML format. As seen from SOAP messages, all data passed is in XML format.
