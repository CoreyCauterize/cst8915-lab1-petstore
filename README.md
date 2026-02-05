# CST8915 Lab 1: Algonquin Pet Store on Azure VM

**Student Name**: Corey Mark-Stewart
**Student ID**: 040770982
**Course**: CST8915 Full-stack Cloud-native Development
**Semester**: Winter 2026

---

## Demo Video

🎥 [Watch Demo Video](https://youtu.be/vzwQfTCRHkY)

---

## Technical Explanations

### Order Service (Node.js)

This service is responsible for workingh with the front to create orders. After orders are created it is sent to the queue. This Stack uses Node.ja with Express as http rest api. AS mentioned before it takes the data from the frontend to send to the queue other services that might need it.


### Product Service (Rust)

This services use Rust api as a way to send information about a product. The front send a request to this api to gather more information about a product to display it on the front. 


### Store Front (Vue.js)

Everything you see on the web page starts here, offering a static page with some http request for more infromations from the Product service.



---

## Challenges and Learnings (Optional)

[Share any interesting challenges you faced during setup, how you solved them,
and what you learned from this lab experience]

One challenage i face was choosing the wrong vm size. did one with 2vcpu and 1gb ram. Made it impossible to work on it.

---

## Acknowledgments

[Optional: Credit any resources, documentation, or people who helped you]
