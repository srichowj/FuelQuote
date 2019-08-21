# FuelQuote
This project serves as platform for the clients of a petroleum industry where users can register as clients and request fuel quote as per their requirements. They can also save their quotes and compare them with the quotes of other clients as well
#Technical Details.

  The project has been developed using the SPring Frame work along with MYSQL as DB.
  The configurations of the project can be seen in the spring-servlet.xml under WEB-INF folder which acts as a dispactcher servlet.
  We have made use of the Spring Annotations @Controller(to define the class as a controller) @RequestMapping(to handle the requests that come in the form URL. This setting has been mentioned in the configuration file spring-servlet.xml under the tag <bean id="viewResolver" **** /bean> )
  Form Data has been handled using the spring MVC features like Model, @ModelAttribute, Model.addObject(), Individual bean classes with getters and setters has been created to handle the data under Model of MVC.
