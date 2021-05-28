
<p align="center">
  <img src="https://user-images.githubusercontent.com/5983943/116801020-7ce76a80-aadc-11eb-9128-92cc1f4d00fe.png" width="100px" align="center" />
</p>
<p align="center">
  <a href="https://csilva2810.github.io/">Hi, I'm Tanish!</a>
</p>

```javascript
import React from 'react'
import ReactDOM from 'react-dom'

const Person = ({ name, jobTitle, country, technologies, hobbies }) => (
  <p>
    Hello, my name is {name}. I'm a {jobTitle} in ${country}. <br />
    I love building things using {technologies}. <br />
    My hobbies are {hobbies}. <br />
    You can visit my personal site at: {personalSite} <br />
    Nice to meet you!
  </p>
)

ReactDOM.render(
  <Person
    name='Tanishraj'
    jobTitle='Front-end Engineer'
    country='India'
    technologies='Javascript and React'
    hobbies='playing video games 🎮, exercising 🏃‍♂️.'
    personalSite='https://github.com/tanishraj/tanishraj/'
  />,
  document.getElementById('root')
)
```
