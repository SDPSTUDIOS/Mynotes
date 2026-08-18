1. Considering the notions of Product and Domain around Lecture 2, Slide 25), is the receptionist part of the product or part of the domain? Please explain!

2. Given the context of the hotel information system as discussed in Lecture 2, describe the Check-Out task in the Task & Support style.
	- Task Description
	- Frequency - How many time would you do that task (34 checkins per day), The overall activity carried out in a daily basis
	- Critical issues handeling - The performance and the throughput of the application or software, in other words hadeling the load
	- Sub tasks / Steps - The steps and tasks to complete checkin in this case
---
	- Task name - Check out
	- Purpose - Check out
	- Trigger - Guest approches the reception and wanna check out
	- Pre condition - The guest should be checked-in first
	- Frequency - Same amount of check-ins happen
	- Critical - Unhandled amount of customer load (Horizontal Scaling or Vertical Scaling)
	- Sub tasks - Return the key to the room, Check room, Check Account and Pay at the end

Problems and variants should be correctly depicted - variants is other ways to perform sub task
without returning the key to the reception the customer can put it into a drop box

3. Identify the typical tasks that a Hotel Information System must support, create a corresponding workflow, and visualise the resulting workflow using a suitable notation, and describe it as a high-level task.

4. What are tacit requirements? Is it possible to perform a validation check on tacit requirements?
	- **This is also known as implicit requirements, These are obvious for Domain experts not the others**

5. The domain model for the hotel information system (around Lecture 2, Slide 31) is incomplete. For example, in most hotels, rooms are by room type (single, double, family etc.). Furthermore, overbooking of rooms is not supported, either. Extend the domain model so that these extensions can be covered.

6. The Check-In task (around Lecture 2, Slide 35) handles two situations: 
		a) The guest has booked in advance;
		b) The guest has not booked in advance, but hopes there is a free room available. Do the following:

7. Split the task description into two task descriptions Check-In a Booked Guest and Check-In a Non-Booked Guest.

8. Discuss the difference between the one-task solution and the two-task one. Which approach is more suitable?

9. Many hotels apply a policy of overbooking, i.e. they book more rooms than the hotel actually has. In practice, not all booked guests turn up and there is no real problem. However, in case too many guests turn up, an emergency solution needs to be found (e.g., allocating guest to a different hotel). Please extend the Check-In task to handle this situation.