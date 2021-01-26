
### Document History
| Version  | Date      | Summary of Changes |
| ---------| ----------| -------------------|
|    1.0   | 19-08-2020| Inital Draft       |

## Content

- [About This Document](#aboutDocument)
  - [Introduction](#Introduction)
  - [Audience](#Audience)
  - [Scope](#scope)
- [Functional overview](#FunctionalOverview)
  - [Introduction](#FIntroduction)

## About This Document <a name="aboutDocument"></a>

### Introduction <a name="Introduction"></a>
This document describes the Merchant API SDK for Web.The SDK is provided
by Zapp and is ready to implement.

### Audience <a name="Audience"></a>
This document describes the Merchant API SDK for Web.The SDK is provided
by Zapp and is ready to implement.

### Scope <a name="scope"></a>
The scope of this document covers integration and implementation of the Web Merchant API.

## Functional overview <a name="FunctionalOverview"></a>

### Introduction <a name="FIntroduction"></a>
This document describes the Merchant API SDK for Web.The SDK is provided
by Zapp and is ready to implement.


### Flow Diagram
![alt text](https://user-images.githubusercontent.com/16609152/105854387-dab37480-600c-11eb-93d5-55a85841267e.jpg)

#### Figure 1 : Flow diagram of user journey



## User journey
--------------------------------------------------------------------------------------------------------------


<p float="left">
 <img src="https://user-images.githubusercontent.com/16609152/105854473-f3bc2580-600c-11eb-9fde-77192e56a80b.jpg" alt="Encryption of sensitive data" width="200px" />
<img src="https://user-images.githubusercontent.com/16609152/105854473-f3bc2580-600c-11eb-9fde-77192e56a80b.jpg" alt="Encryption of sensitive data" width="200px" />
<img src="https://user-images.githubusercontent.com/16609152/105854473-f3bc2580-600c-11eb-9fde-77192e56a80b.jpg" alt="Encryption of sensitive data" width="200px" />
<img src="https://user-images.githubusercontent.com/16609152/105854473-f3bc2580-600c-11eb-9fde-77192e56a80b.jpg" alt="Encryption of sensitive data" width="200px" />
</p>


## Sample Code

```javascript
function generateInvoiceNumber(){
	let invoice = Math.round(Math.random() * 100011);
	let invoiceNumberBox = document.getElementById('invoiceNumber');
	invoiceNumberBox.innerHTML="Invoice #"+invoice;
}
```
