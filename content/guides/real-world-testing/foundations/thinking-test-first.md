# Thinking Test First

Now that we understand that testing is a mindset, we need to discuss how this mindset plays out in the day to day work of software development. As new feature requests or bug fixes come in, you and your team should be thinking first about how you are going to test the application code related to these changes. These discussions should not be held in isolation, but should always incorporate both dev and QA teams. Even if your QA team is primarily doing manual testing, their input is incredibly valuable. They can help provide the test cases that they would expect to run against this new feature and you can then translate those test cases into automated tests. Since QA teams think differently then developer teams, their insights, experience and testing knowledge is incredibly valuable. This does not mean however, that the automated tests replace manual testing. Both are valuable and important and you should always do both whenever possible. The automated tests simply provide another layer of confidence and hopefully save the QA team some time as they won't have to manually test as much.

If you do not have a dedicated QA team, then the development team should be having discussions on what kinds of tests are going to be necessary to ensure this new feature is working correctly. An easy way to do this is to start with the end goal and work backwards. What does this new feature need to do? Once you understand that, you can break the problem down into small incremental steps, and translate those steps into tests. This way you have a clear path to achieve your goal and tests that will confirm everything is working properly or not, each step of the way.

Thinking test first is how you build up a suite of tests over time that will help to give your team confidence and peace of mind that your application is working properly.