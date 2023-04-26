# WEKEA : IKEA-motivated clone coding project

![Vector](https://user-images.githubusercontent.com/37966668/232393450-f45f8d99-6001-4ce0-9e19-c2c0bebd19ae.png)

![giphy](https://user-images.githubusercontent.com/37966668/232397033-2bbaa8d7-382f-494b-9a8d-d7a3180d966c.gif)

<br />

![Group 3](https://user-images.githubusercontent.com/37966668/232392845-3958e8f3-0bfc-4734-8423-cd8a47ba55a3.png)

## Team uniC5n - FrontEnd

- <a href="https://github.com/ggkim0614">George Kim<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/hongyeollee"/></a>
- <a href="https://github.com/suny0ung">Sunyoung Choi<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/hongyeollee"/></a>

<br />

<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/sass-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="52" height="52" /></div>


## Team uniC5n - BackEnd

- <a href="https://github.com/minseoya">Minseo Kim<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/minseoya"/></a>
- <a href="https://github.com/lsg622">Sungkeun Lim<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/lsg622"/></a>
- <a href="https://github.com/Dongrang072">Sanghyun Choi<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/Dongrang072"/></a>

<br />

<div style="display: flex; align-items: flex-start;"><img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon" width="52" height="52" /><img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="52" height="52" /></div>

<br />

Special Thanks to - <a href="https://github.com/parkseyik">박세익 <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/parkseyik"/></a>

<br/>

# WEKEA - furniture e-commerce platform clone coding project

- This project was completed as a part of the curriculum of <a href="https://github.com/wecode-bootcamp-korea">Wecode</a>, a coding bootcamp located in Korea.

<br/>

# 👨‍💻 Features/Pages devleoped:
1. Sign In / Sign Up Page (George)
2. Landing Page (Sunyoung)
3. Product Listing Page (Sunyoung)
4. Product Details Page (Sungyoung)
5. Showroom Page (George)
6. Purchased Items Page (George)
7. Cart Page (George)
8. Order/Payment Page (George)

<br />

#### ** 1. Sign In / Sign Up **

**Sign In** - All inputs are checked with regex validations - once they pass regex validations from both cliend and server side, user receives a JWT(Json Web Token) from the server. JWT is stored in the local storage, and used whenever a request requires an authorization. User's name gets also displayed once user receives their username passed along with JWT.

https://user-images.githubusercontent.com/37966668/232360969-961bce36-2904-4a2a-bff8-55f712371490.mov

**Sign Up** - Checked with multiple regex validations(Birth/YYYY-MM-DD, account/XXXX@XXXX.XX, phone number/XXX-XXXX-XXXXX 등)

https://user-images.githubusercontent.com/37966668/232361004-cde3fa02-0019-4541-a264-1b11b847047c.mov

<br />

#### ** 2. Landing Page **<br>

Landing page is consisted of components such as banner with a hyperlink to showroom page, recommended items listed in the section below, etc.

**Navigation** - After signing in, username received with JWT is displayed on the navigation bar. Various hyperlinks are mapped with constant datas inside the source code - every link is linked to their destinated pages.

https://user-images.githubusercontent.com/37966668/232379658-8921f658-8999-41a2-9d33-0a32c5284a2b.mov

**Search feature** - Search feature was designed so that items can be searched with not only their names but also their categories. Every an input event is fired, the value inside the input field is sent to server as a payload, asking for all the items that match the search value sent in the payload.

https://user-images.githubusercontent.com/37966668/232379785-4304a413-f12d-4f0c-a582-3aff6e79cf36.mov

<br />

#### ** 3. Showroom Page **<br>

Page showing showroom pictures displaying a collection of furnitures, and also the mini carousel next to the image, enabling users to browse which items were displayed in the image. All the items inside the carousel are clickable, routing to their detail pages.

https://user-images.githubusercontent.com/37966668/232380673-85340074-ad54-403c-90f7-4c7edb4b3e87.mov

<br />

#### ** 4. Product List Page **<br>

**Ascending/descending price filter feature** - All the items mapped on the list page can be re-sorted in the price ascending/descending order. Requests are sent dynamically from the front-end by dynamically manipulating the query strings used for requesting to the server.

https://user-images.githubusercontent.com/37966668/232383804-1432ed20-cad6-4cf0-b63b-40c0a642b446.mov

<br />

#### ** 5. Product Details Page **<br>

Pages with details of each product. Dynamically routed with query strings, so that the same page with equal layouts can display different information when different items are clicked.

https://user-images.githubusercontent.com/37966668/232384212-2c71ce5b-e667-4e98-97e5-1034e97962fe.mov

<br />

#### ** 6. Cart-Order-Payment Flow **<br>

Deleting/modifying the amount of item made possible in the cart page, and payment made possible during the order-payment process. All items purchased by the user can be checked in the purchase items page. All the features included in the flow requires a authorization token that is unique to each user.

https://user-images.githubusercontent.com/37966668/232386906-437d0a4a-12de-4964-ba1a-a6e0d69213cf.mov

<br />

#### ** 7. Purchased Items / Writing/deleting review feature **<br>

If user has a record on the purchase of a specific item, writing/deleting review is possible. Once a user tries to leave a review to the items that the user haven't purchased, the user's action will receive an alert feedback, notifying that one has to purchase the item to leave a review.

https://user-images.githubusercontent.com/37966668/232387897-96f1cba1-d256-44ee-8933-32db6449efbc.mov

<br />








