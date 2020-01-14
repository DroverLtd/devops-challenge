<img src="./static/drover-logo.svg" width="200">

# Test Automation

Drover is a VC-backed, growth-stage marketplace company offering monthly, all-in car subscriptions to customers who want to experience car ownership as it should be: digital, flexible and at a fair, transparent price. For some more detail, check out our press coverage in TechCrunch, Forbes or CityAM.

We want to build ever more extraordinary digital experiences for our users and we need your help: come on board and join our 20-strong engineering team spread across London and Lisbon busy changing the automotive landscape.

## Assignment
### What You Should Know

This is the website we are going test against: https://staging-fe.drover-test.com/

This is our "pre-production" environment and before we ship anything to production we do extensive testing on this environment. Currently, we only operate inside of UK so during your tests, make sure you are using a UK phone number and postcode.

### The Use Case

Drover's one the most important flows is "sign up" during the booking process. So you want to make sure that at least the basic flow is working properly. So starting from the home page you are going to search for PCO cars and do the sign up using automation tools.

#### Step-by-step
* Visit the Drover's (staging environment) home page.
* Click the link "Looking for PCO cars?".
* Click on the blue button "Find your PCO car".
* Pick a car.
* On the car details page you will a section saying "To book this car, you’ll need to create an account with us." so click on the blue button labeled "Create an account".
* Fill out all the required fields and proceed with "Create an account".
* Fill out a postcode and insurance history.
* We will ask you for your driver license data. Use any file on your computer and click on "Next".
* If you get to a page saying "You’re all set to start your car subscription!" that's it. :)

## What Do We Expect From You?

* As you noticed, during the `step-by-step` flow we didn't mention any validation checks. You will be the judge of what you think it's important to check during the user flow.
* You can use the technology you think it's going to be the best. At Drover we have CI/CD in place so during the process of deciding the right technologies to automate this use case keep that in mind.
* Your test suite is expected to grow over time and also to be maintained by others so overall organization and documentation are highly appreciated.

------

## Questions?

If you have any problems or questions please reach out to us at techleads@joindrover.com
