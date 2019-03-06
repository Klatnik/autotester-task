# ROI Hunter Test Automation task

Your task is to cover part of the application https://trello.com.

Please cover these parts:

**1)** Create a new Board.
https://www.useloom.com/share/01b726d60e58439db47e4933d7d567f7

**2)** Add a new List to the existing Board (The Board will always be created via API at the beginning of the test)
https://www.useloom.com/share/02cd952497334c5a8a5cbbf49903addf

**3)** Add a new Card into the existing List and fill it (the board and List will always be created via API at the beginning of each test run)
https://www.useloom.com/share/7690c5813608407fa75df161523e8e8e

Note: Image upload, adding of Checklist and Description are mandatory. If you decide to test something more we will appreciate it.

**4)** Create a complete end-to-end test flow which will run all the previous cases in the browser window (Board creation, adding List into this Board, inserting and filling of a new Card in this List)

---

### Useful information

Trello API Docs: https://developers.trello.com/v1.0/reference 

Please prepare this task in Java. For the browser automation use Selenium Webdriver (ideally ChromeDriver).
You can choose any framework you want. Small hint: we are using test framework TestNG, HTTP request client library Unirest and for serialization/deserialization we use Jackson.

Please try to create nice, readable and easy to maintain code. Also please focus on reusability and stability. It would be also nice to cover suitable methods by some unit tests. 

Place your code to a public Git repository (for example Github) and send us the link.

Contact: libor.bitala@roihunter.com
