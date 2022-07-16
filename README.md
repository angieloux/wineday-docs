# **T3A2 (Part A) Documentation**

## **Purpose**
This developer was an approached by a wine retailer, *WineDay*, based in the Yarra Valley. 

The successful family-run business has survived the last 20 years on good management, wonderful reviews, word-of-mouth, a catchy slogan (*"**every**day is WineDay"*) in person sales & wine demonstrations, but alas, COVID-19 has had a dramatic impact on their profitability. 

After securing a contract with a freight company for domestic deliveries, the key decision makers requested the development of an online store to boost: 
1. wine sales,
2. reach of their products, and
3. marketability of their brand to a wider audience

> *Small disclaimer: this didn't happen, and this business doesn't exist.✨*

The app's purpose is to fulfil the needs of the business as stated above. Simply, it will utilise a database of available wine with specific attributes (i.e. varietal, region, price, score, etc) and allow users to filter and search by these. The user will also be able to sign up,  make purchases and see their order history. 

If time allows, for this project, a user will also be able to save their wine preferences and the app will be able to give them new wine recommendations based on that. 

## **Functionality/Features**
The below are features associated with the first-stage MVP development of the WineDay app. 

### **All users**
Anyone that visits the WineDay site will be able to access the following features: 

- Information about the business (about us, contact details, etc)
- Search for a wine by keywords
- Filter wines by region/price/score/varietal
- Sign up for an account
- Log into an account
 
### **Customer (logged in user)**
Additionally, once authenticated, a logged in customer can:

- Add wine to cart
- Remove wine from cart
- Check out
- Log out
- View order history

### **Potential future features (or, if time allows)**
- Create a admin profile that has exclusive authority to update/delete/add new wine listings & view/amend user profiles.
- A logged in user can add their wine preferences to their profile & recommendations can be made by the app based on this
- Add "just in" tab for new wines
- Add "recommended" tab for recommended wines
- Add "food pairings" tab for recommended food pairings
- Search wines by description ("dry", "fruity")

## **Target Audience**

The target audience is anyone that likes wine (so, a wide scope) that is also in the delivery/pickup region of WineDay (i.e., people based in Australia, at this stage). This includes both potential customers looking to make a purchase and existing customers either checking on orders or making additional purchases. In future revisions of the app, this scope will expand to include people looking for recommendations of wine based on their preferences.  

Additionally, on the business-side, the target audience also extends to the employees of WineDay who can use a user-friendly UI to see stock levels when interacting with customers in store. 

Lastly, if an admin user profile is implemented in the MVP version of this app, it will also include the person/s in charge of maintaining wine listings and user profiles on the app. 

## **Tech stack**

|Front-end|Back-end|Database|Project Management|Utilities|DevOps|
|--|--|--|--|--|--|
|React.js|Ruby (v2.7.5p203)|PostgreSQL|Trello|Draw.io|GitHub|
|JavaScript|Rails (v6.1.6)|||Balsamiq|VSCode|
|CSS3||||Visual Paradigm||
|HTML5||||||
|Material-UI||||||

## **User Stories**

|As a|I want to|so that I can                         |
|----------------|-------------------------------|-----------------------------|
|Customer|be able to browse all available wines|see what is available at a glance to be able to decide what to purchase
|Customer|see company information about WineDay|to assess company history, location, delivery areas and trustworthiness as a vendor
|Customer|search for a wine by a particular keyword|find a wine quickly instead of scrolling for a long time
|Customer|filter wines by attribute (region, vintage, region, etc)|streamline my wine purchasing decisions & help the decision process if I am not sure exactly which wine to buy
|Customer|add and remove items from my cart|change my mind if I don't want to commit to a purchase or add more that I do want
|Customer|securely check out items in my cart|make a purchase of my desired wines
|Customer|view my order history|to keep track of what I have ordered in the past and what I do/don't want to order again
|Customer|log in and out|to track my purchases and keep my account private and secure
|Admin|log in and out|securely access the admin-only dashboard and log out when done to maintain security
|Admin|view/create/amend/delete user profiles|to make necessary changes or sign up new customers
|Admin|view/create/amend/delete wine listings|to fix errors or make necessary stock changes as required by the business

> 🧁 *Note:* the admin user role is a sprinkle at this stage, and not intentionally being developed in the MVP (unless time permits).


## **Application Architecture diagram**

![Application architecture](./diagrams/application-architecture.png)
## **Dataflow diagram**
Dataflow (role: customer)
![Application architecture](./diagrams/dataflow-user.png)
Dataflow (role: guest)
Anyone who visits the site will be able to have access to search/browse/filter functionality, but will be prompted to log in/sign up if they want to add things to their cart and check out. 
![Application architecture](./diagrams/dataflow-guest.png)
## **Wireframes**
![Wireframes demo - desktop](./wireframes/Wireframes-demo-desktop.gif)
![Wireframes demo - mobile](./wireframes/Wireframes-demo-mobile.gif)

<details>   
  <summary>Desktop wireframe screenshots</summary>

  ![Wireframe screenshot 1 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.29.51%20pm.png)
  ![Wireframe screenshot  (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.30.12%20pm.png)
  ![Wireframe screenshot 3 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.30.39%20pm.png)
  ![Wireframe screenshot 4 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.30.51%20pm.png)
  ![Wireframe screenshot 5 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.31.07%20pm.png)
  ![Wireframe screenshot 6 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.31.15%20pm.png)
  ![Wireframe screenshot 7 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.31.20%20pm.png)
  ![Wireframe screenshot 8 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.31.35%20pm.png)
  ![Wireframe screenshot 9 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.31.46%20pm.png)
  ![Wireframe screenshot 10 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.31.56%20pm.png)
  ![Wireframe screenshot 11 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.32.19%20pm.png)
  ![Wireframe screenshot 12 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.32.25%20pm.png)
  ![Wireframe screenshot 13 (desktop)](./wireframes/desktop/Screen%20Shot%202022-07-15%20at%208.32.30%20pm.png)
  </details>

  <details>
  <summary>Mobile wireframe screenshots</summary>

  ![Wireframe screenshot 1 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.32.40%20pm.png)
  ![Wireframe screenshot 2 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.32.45%20pm.png)
  ![Wireframe screenshot 3 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.32.49%20pm.png)
  ![Wireframe screenshot 4 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.32.53%20pm.png)
  ![Wireframe screenshot 5 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.32.58%20pm.png)
  ![Wireframe screenshot 6 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.03%20pm.png)
  ![Wireframe screenshot 7 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.12%20pm.png)
  ![Wireframe screenshot 8 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.08%20pm.png)
  ![Wireframe screenshot 9 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.18%20pm.png)
  ![Wireframe screenshot 10 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.23%20pm.png)
  ![Wireframe screenshot 11 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.29%20pm.png)
  ![Wireframe screenshot 12 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.37%20pm.png)
  ![Wireframe screenshot 13 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.43%20pm.png)
  ![Wireframe screenshot 14 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.49%20pm.png)
  ![Wireframe screenshot 15 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.54%20pm.png)
  ![Wireframe screenshot 16 (mobile)](./wireframes/mobile/Screen%20Shot%202022-07-15%20at%208.33.59%20pm.png)

  </details>

## Project management workflow (Trello)
<details>
  <summary>Click to expand</summary>

![Trello screenshot 1](./trello-screenshots/Screen%20Shot%202022-07-01%20at%201.52.28%20pm.png)
![Trello screenshot 2](./trello-screenshots/Screen%20Shot%202022-07-05%20at%204.22.15%20pm.png)
![Trello screenshot 3](./trello-screenshots/Screen%20Shot%202022-07-06%20at%201.30.43%20pm.png)
![Trello screenshot 4](./trello-screenshots/Screen%20Shot%202022-07-06%20at%205.02.47%20pm.png)
![Trello screenshot 5](./trello-screenshots/Screen%20Shot%202022-07-06%20at%205.36.51%20pm.png)
![Trello screenshot 6](./trello-screenshots/Screen%20Shot%202022-07-06%20at%209.34.33%20pm.png)
![Trello screenshot 7](./trello-screenshots/Screen%20Shot%202022-07-06%20at%209.35.48%20pm.png)
![Trello screenshot 8](./trello-screenshots/Screen%20Shot%202022-07-06%20at%209.37.00%20pm.png)
![Trello screenshot 9](./trello-screenshots/Screen%20Shot%202022-07-07%20at%2012.12.41%20am.png)
![Trello screenshot 10](./trello-screenshots/Screen%20Shot%202022-07-07%20at%2012.12.46%20am.png)
![Trello screenshot 11](./trello-screenshots/Screen%20Shot%202022-07-07%20at%2012.13.45%20am.png)
![Trello screenshot 12](./trello-screenshots/Screen%20Shot%202022-07-07%20at%2012.13.53%20am.png)

</details>