
# North Vacation Booking - Test Plan

**Name:** Aden  
**Assignment:** Learning Practice 07 - Test Planning  
**Application:** North Vacation Booking  
**Status:** Test Planning

## 1.  Testing Environment

### Test Objectives 
1.  Check that users can select a rental, provide booking dates, select number of guests and create a booking.
2.  Test that the application does not allow invalid bookings and shows the booking information accurately.

### Scope of the Study
-- Picking a rental
- Dates for check-in and check-out
- Number of persons
- Making bookings
- View reservations
- Values increasing and decreasing
- Resetting of values
- Validate the form

### Beyond the Scope
- Processing payments
- Email notice
- Integrations with third parties
- Tests for performance

### Testing Basis
Requirements for North Vacation Booking and functionalities of the program as specified in the README.

### Assumptions & Limitations
- A functioning app to test against.
- Test will be done within five working days.
- Developers are there to help you out in case of any issues.

## 2. Roles and Responsibilities

| Role | Responsibility | When Involved | Communication |
|---|---|---|---|
| Tester | Creates and runs test cases and reports bugs | Days 1-5 | Communicates with developers |
| Developer | Fixes bugs and provides the application | During testing | Communicates with tester |
| Product Owner | Reviews requirements and approves the release | Beginning and end | Communicates with team |

## 3. Test Approach

Testing will include component, integration, and system testing.

### Test Types
1. Functional Testing - Verify that application features work correctly.
2. Regression Testing - Make sure previously working features still work after changes.

### Test Techniques
1. Boundary Value Analysis - Test minimum and maximum guest limits and date boundaries.
2. Equivalence Partitioning - Test valid and invalid input groups.

### Manual and Automated Testing
Manual testing will check rental selection, booking creation, dates, and guest controls.

Automated testing may use Jest if the application source code and testing framework are available.

### Test Scenarios
1. Select a rental.
2. Enter valid check-in and checkout dates.
3. Try entering an invalid checkout date.
4. Increase the guest count.
5. Decrease the guest count.
6. Verify that guest limits are enforced.
7. Create a booking.
8. Verify that the booking appears in the booking list.
9. Reset values where supported.

### Test Deliverables
- Test plan
- Test cases
- Test results
- Bug reports
- Test completion report

## 4. Test Requirements

### Test Environment
A local or online version of the North Vacation Booking application.

### Browsers and Devices
- Google Chrome
- Mozilla Firefox
- Desktop computer
- Mobile browser viewport

### Testing Tools
- GitHub
- Git
- Visual Studio Code
- Browser Developer Tools
- Jest if automated testing is available

### Test Data
- Rental names
- Valid dates
- Invalid dates
- Different guest counts
- Empty booking fields
- Sample bookings

### Access and Permissions
The tester needs access to the application and GitHub repository.

### People and Training
The tester needs basic knowledge of software testing. Developers will provide help when necessary.

## 5. Risk Register

| Risk | Type | Likelihood | Impact | Mitigation |
|---|---|---|---|---|
| Invalid dates are accepted | Product | Medium | High | Test date validation |
| Guest count becomes negative | Product | Medium | High | Test minimum guest limits |
| Booking does not display | Product | Medium | High | Test booking list |
| Testing environment is unavailable | Project | Low | High | Check environment before testing |
| Not enough testing time | Project | Medium | Medium | Prioritize important features |

## 6. Entry Criteria

Testing can begin when:

1. The application is available and opens successfully.
2. Test cases have been created and reviewed.
3. Test data is ready.
4. Testing tools are installed.
5. The tester has the necessary access.

## 7. Exit Criteria

Testing is complete when:

1. 100% of high-priority test cases have been executed.
2. At least 95% of all planned test cases have been executed.
3. At least 90% of test cases pass.
4. No critical or high-severity bugs remain unresolved.
5. All important fixes have been retested successfully.
6. The final testing report is completed.

## 8. Test Schedule

| Activity | Responsible | Time | Dependency |
|---|---|---|---|
| Review requirements | Tester and Product Owner | Day 1 | Requirements available |
| Create test cases | Tester | Day 2 | Requirements reviewed |
| Set up testing environment | Developer and Tester | Day 2 | Application available |
| Execute test cases | Tester | Day 3 | Test cases ready |
| Report and fix bugs | Tester and Developer | Day 4 | Testing completed |
| Retest and write summary | Tester | Day 5 | Fixes available |

## 9. Communication Plan

| Information | Audience | Method | Frequency |
|---|---|---|---|
| Testing progress | Project team | Team meeting | Daily |
| Bug reports | Developer | GitHub Issues | When bugs are found |
| Testing problems | Tester and Developer | GitHub comments | When needed |
| Test results | Product Owner | Written report | End of testing |
| Final summary | Entire team | GitHub repository | Day 5 |

