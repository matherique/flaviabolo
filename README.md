# 🎂 My mom website using nextjs + google spreadsheet 
this is my mom website, using nextjs and google spreadsheet API to get a list of all type of cakes that she makes

## 💪 Motivation 
my mom need a easy way to send to their customers a price list, and I'm not good with Photoshop like software's 😢
So I make a "simple" site to her and now she only share a link. She don't have patience to learn how to use a admin panel and edit the list and prices, so I use Google SpreadSheet API to get all information from a spreadsheet, now she can edit in the spreadsheet and see the changes in 1 hour.

## 🧰 Tech 

Wrote using **next** with **typescript**, using the build in serveless API that nextjs provides, Styled Components to "easy" styling, 
**Vercel** for cloud, the free options its ok intil we have more and more access, **Jest** and **React Testing Library** for test

## 🖥️ "Tests"
I tried to write some tests to the components and the API route, its not a good test suit, i'm learning 

## 🔨 Usage

Install the packages with **npm** or **yarn**, your preference 
```bash
npm install
```
or 
```bash 
yarn
```

Fill the .env file with:
```bash
SHEETID= // sheet id that contains all information
GOOGLE_CLIENT_EMAIL= // email provides by Google SpreadSheet API 
GOOGLE_PRIVATE_KEY= // private key provide by Google SpreadSheet API 
```
Get this information in [Google Developer Console](https://console.developers.google.com/)

Run in dev mode using **dev** script 



## ✔️ TODO in the future
a little list to do when I revisited this project
- [ ] add image suport, mabe in the spreadsheet or in some google drive folter ? i dont know 
- [ ] dark mode ? will be cool 🌗
- [ ] write better tests
- [ ] refactoring architeture 
