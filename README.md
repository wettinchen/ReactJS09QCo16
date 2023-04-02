## ReactJS Chapter 09
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 Reactjs 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6PrE9srvEn8nbhOOyxnWXfp
### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## ReactJS Chapter 09
   Quick Concept outline
   中文摘要說明與重點提問
   
###  1. Intro 
        教學影片固定的開頭和摘要說明

###  2. Set up and clean up
        設定與清理 dependencies
        npm i react-icons --save-prod

        為什麼 ListItem 的 key 可以移除?

###  3. Creating a Form Component <Code更動>
        說明加入表格的原因?
        新增 AddItem.js，
        <form></form> 包含 <label></label> <input> <button></button>
        從 react-icons 匯入 { FaPlus }
        匯入 AddItem.js 至 App.js

###  4. Adding CSS Styles to the form <Code更動>
        加入 CSS 表格樣式

###  5. Sending props to the form component <Code更動>
        在 App.js 指派一個新的 加入項目的 Array
        新增表格的功能至 AddItem 中
        在 App.js 指派 handleSubmit 功能
        並新增參數於 App.js
        在 App.js 新增表格功能的參數至 AddItem 中
        在 AddItem.js 新增表格功能的參數至 AddItem 中

        const [newItem, setNewItem] ...
        const handleSubmit ...

###  6. Making a controlled input component <Code更動>
        在 AddItem.js 設定表格可以加入的項目(值和隨著值改變的事件)，並展示顯示內容。

        value...
        onchange...

###  7. The handleSubmit function <Code更動>
        在 handleSubmit 功能中設定防止預設重置
        送出後格子內依然為空格
        設定顯示回傳的內容

        onSubmit={(event) => handleSubmit(event)}
        const handleSubmit ... {
                ...
        }
       
###  8. The addItem function <Code更動>
        刪除 handleSubmit 顯示回傳的 Code
        在 App.js 新增加入項目的功能，藉由 object 的 id, checked, item
        const listItem ...

###  9. The setAndSaveItems function - D.R.Y. (don't repeat yourself) <Code更動>
        新增新功能，將重複的部分取代
        const setAndSaveItems ...

### 10. Adding new items <Code更動>
        在 handleSubmit 功能做最後設定，
        便可以加入新項目。

### 11. Loading state from localStorage
        更改設定便能從使用者終端抓取資料

### 12. Search Functionality <Code更動>
        希望搜尋功能可以協助
        添加更多項目和縮減項目，
        以便選取特定符合需求的項目。

### 13. Building the search input component <Code更動>
        新增 SearchItem.js，
        當送出搜尋項目後，搜尋欄位不會重置

### 14. Props for the search input component <Code更動>
        在 App.js 指派一個新的 搜尋項目 Array
        新增搜尋的功能至 AddItem 中
        匯入 SearchItem.js 至 App.js
        並新增參數於 App.js

        const [search, setsearch] ...

### 15. Completing the controlled search input component <Code更動>
        新增 CSS 樣式於 index.css 或 其他 css
        新增 SearchItem 的 參數和 input 的設定
        將 SearchItem 欄位 改至 AddItem 欄位 下方

### 16. Adding search functionality with filter() <Code更動>
        使用 filter 完成搜尋功能設定

### 17. Review of Controlled Form Input Components
        複習
        AddItem --> SeatchItem

### 18. The useRef hook
        當送出項目後，按鈕依然為綠色，
        要移除 focus 變為白色。
        在 AddItem.js 匯入 useRef，
        在 input 和 button 新增

        ref ... 
        onClick ...


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
