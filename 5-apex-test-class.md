---
layout: module
title: Module 5&#58; Apex Test Classes
---

To facilitate and promote the development of robust, error-free code, Apex Code requires the creation and execution of unit tests. Unit tests are class methods that verify whether a particular piece of code is working properly. Unit tests are written in Apex Code and annotated with the testMethod keyword (we will go into formal syntax in the next section).


It is important to understand that test methods are required to deploy Apex to a production environment. They are also required if your code is going to be packaged and placed on Force.com AppExchange. The test methods must provide at least 75% code coverage. Think of a test method as 'Apex code that tests other Apex code.' Code coverage is calculated by dividing the number of unique Apex code lines executed during your test method execution by the total number of Apex code lines in all of your trigger and classes. (Note: these numbers do not include lines of code within your testMethods)


It is also important to not think of test methods as simply a requirement by the Force.com platform. It should not be an afterthought. Writing test methods should be a critical part of Force.com development and they are required to ensure your success. Test methods provide test automation which can enable greater QA efficiency. It also provides an automated regression testing framework to validate bug fixes or future development enhancements.



<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="4.2-exercise-edit-and-test-trigger.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="5.1-exercise-adding-a-test-class.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
