# Coding Challenges

The following exercises are coding challenges/technical exercises that have been sent by students and teachers. They are meant as extra practice and to get a feel for what companies will ask for. Other coding challenges can be found in a pdf format as they were sent to the candidate.

#### 1. Total and Tax
- Return total price and add tax to each price
- Return entire object.
- Return item with highest price
  ​

```javascript
const basket = {
  basket: [
    { name: "Item 1", price: 89.99 },
    { name: "Item 2", price: 88.13 },
    { name: "Item 3", price: 99.23 },
    { name: "Item 4", price: 93.23 }
  ]
};
```

#### 2. Random Numbers
Print numbers from 1-10 in a random order. Elements must only be printed once.

#### 3.Node Picker

````html
<h1>Node Picker Assignment</h1>
<h2>Requirements</h2>
<ul>
  <li>
    A list of Nodes, each with a reference to their parent, should be displayed
    hierarchically
  </li>
  <li>The user should be able to select nodes</li>
  <li>Selected nodes should be visually highlighted somehow</li>
</ul>
<h3>Bonus tasks</h3>
<ul>
  <li>
    The user should be able to select groups (a node and its immediate children)
    without selecting every node individually).
  </li>
  <li>
    Add some tests where you think the code could benefit from having tests.
  </li>
</ul>
<p>
  The solution does not need to be visually styled in any special way. The
  hierarchy and the selection should be visible of course.
</p>
```` 

````javascript 
const nodes = [ {id: 0, name: 'aaa' }, {id: 1, name: 'bbb',
parent: 0 }, {id: 2, name: 'ccc', parent: 0 }, {id: 3, name: 'ddd' }, {id: 4,
name: 'eee', parent: 3}, {id: 5, name: 'fff', parent: 3}, {id: 6, name: 'ggg',
parent: 3}, {id: 7, name: 'hhh' }, {id: 8, name: 'iii', parent: 7}, {id: 9,
name: 'jjj', parent: 8}, {id: 10, name: 'kkk', parent: 9}, {id: 11, name: 'lll',
parent: 9}, {id: 12, name: 'mmm', parent: 9}, {id: 13, name: 'nnn', parent: 8},
{id: 14, name: 'ooo', parent: 13}, {id: 15, name: 'ppp', parent: 13}, {id: 16,
name: 'qqq', parent: 13}, {id: 17, name: 'rrr' }, {id: 18, name: 'sss', parent:
17}, {id: 19, name: 'ttt', parent: 17}, {id: 20, name: 'uuu', parent: 19}, {id:
21, name: 'vvv', parent: 19}, {id: 22, name: 'www', parent: 17}, {id: 23, name:
'xxx', parent: 17}, {id: 24, name: 'yyy', parent: 23}, {id: 25, name: 'zzz',
parent: 23}, ]; ```
````
#### 4. Create a tree showcase
[This challenge documentation can be found on github.](https://gist.github.com/Vinesse/65e5336a90a3228e20eb4babd9312793) 

#### 5. Front & Back
If it is possible, you can prepare the following (depending on what you can do) in order to have a starting point with the team afterwards:
* **React App Frontend** 
    - Display list (with heading), which for example lists articles
* **Backend**
    - CRUD principle (create, read, update, delete entries), preferably with MongoDB on framework express.js

#### 6. H e l l o
**Input**
```javascript
`hello`
```
**Output**
```javascript
`h e l l o`
```
**Other Points**
* The string must not have any whitespace on the back or front of the string. 
* Check if input is a string. If it's not a string, throw and error. 

#### 7. Trial Pack
* Create a view for the following layout - you can find the layout [here](./challenges/challenge_layout.pdf).

You should use:
* Vue.js (this was the original request by the company - students can try to use Vue, but for the purposes of practicing, they can also use React)
* SCSS

* User story:
  - When on the trial pack page, I have the opportunity to select a size from 1 to 5 for my trial pack.
  - The image of the trial pack changes, depending on which diaper size I choose.
  - Sizes 1 and 2 contain the 99% water wipes and sizes 3 to 5 contain the sensitive wipes. All sizes contain a small pack of (10) diapers.

* In the section “Dein Testpaket enthält” you can see a preview image of the diaper and the wet wipes. The image of the wet wipes changes, depending on the selected diaper size.
* The trial pack page should be fully responsive.

* Please upload your work to a public Git Repository of your choice (GitHub, Bitbucket, …)

* You can find a demo of the page here: https://www.lillydoo.com/de/testpaket
