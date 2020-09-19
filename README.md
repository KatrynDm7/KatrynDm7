> I'm a developer, so let me introduce myself in code!

![Image of Katryn Dmitruk](https://firstlinesoftware.com/uploads/CACHE/images/content/news/2020/08/05/5eaf4867-6ea7-49f2-a581-0746dc4faab3/6d8159e1ea3229f244b6953e3bc6fefb.png) 

```javascript
// HTML
<div id="introduction-block"></div>

// JS: Introduction block
const letMeIntroduceMyself = arg => {
    const introductionBlock = document.getElementById('introduction-block');
    
    if (!introductionBlock) {
        return;
    }

    const helloText = '<div>Hi there 👋🏾 👋🏼 👋🏿 👋🏻!<br/>' 
        + 'I\'m Katryn, Tech Lead Frontend Developer,<br/>'
        + 'Speaker, Writter on Medium, and Ambassador at WomenTech Network</div>';
    
    const skills = 
        '<ul>'
            + '<li>My 3 main skills are:'
                + '<ul>'
                    + '<li>JavaScript</li>'
                    + '<li>AngularJS</li>'
                    + '<li>Angular 2+</li>'
                + '</ul>'
            + '</li>'
        + '</ul>'
        +'<ul>'
            + '<li>Also, during my 9+ experience in tech I worked with:'
                + '<ul>'
                    + '<li>TypeScript</li>'
                    + '<li>NodeJS</li>'
                    + '<li>Java</li>'
                    + '<li>PHP</li>'
                    + '<li>MySQL</li>'
                    + '<li>etc</li>'
                + '</ul>'
            + '</li>'
        + '</ul>';
    
     const total = '<div>These skills give me the ability to see the whole picture when \n'
        + 'designing the project architecture</div>';
    
    const email = '<div>My E-mail: dmytrukk@gmail.com</div>';
    
    introductionBlock.innerHTML = helloText + skills + total + email;   
}

letMeIntroduceMyself();
```
