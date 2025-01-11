# LWC and Comet 
Subscribe to Comet based integration events such as PE, CDC, Push Topic from LWC using EMP API.

Use case:
1. When an opportunity is updated and status is moved to closed won then publish a platform event with details such as Opportunity Name and Opportunity Owner

2. Grab that event in a LWC component and show notification on screen.

Solution:
1. Platform Event is defined can be found in objects
2. Flow is created for update opportunity and publish an event on update n status match
3. Refer to LWC component to subscribe for event on page and open developer console to vie result

How to Test:
1. Edit opportunity record page and add this component to record page.
2. Subscribe to listen (Click)
3. Edit record and change status to Closed Won
4. bserver developer console