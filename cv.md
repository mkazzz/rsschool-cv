# Michał Kazek
### _Junior Front End Developer in progress_  

![mkazz-profile-photo](mkazzz.png)


#### Contact me:  

 >**Address**: Gdynia, Poland
 >**LinkedIn**: [LinkedIn](https://www.linkedin.com/in/mat%C3%ADasg%C3%B3mezbonazzi/)  
 >**Whatsapp**: [WhatsApp](https://wa.me/+48503517888?text=WhatsApp)  
 >**E-mail**: mkazek+rs_school@gmail.com 

### About Me 
My love coffee and coding. I work for an HVAC company as an ERP system developer, but it's time to change something in my life. I started this course, because I want to 


### Skills
 - WebDev: HTML + CSS + JavaScript + PHP
 - DataBases: MySql, Oracle, Firebird
 - Programming Languages: Java (basic), Python (basic)

### Code Examples

```javascript
class App extends Component {
  constructor(props) {
    super(props);
    this.state = {
      loginPage: [],
      ordersScreen: [],
      listaZlecen: []
    }
  }
  componentDidMount() {
    var loginPage = [];

    loginPage.push(<Loginscreen parentContext={this} />);
    console.log('this from App: ' + this);
    this.setState({
      loginPage: loginPage,
      id_pracownika: this.setState.id_pracownika
    })
  }
  render() {
    return (
      <div className="App">
        {this.state.loginPage}
        {this.state.ordersScreen}
        {this.state.listaZlecen}
      </div>
    );
  }
}
```


### Education: 
- **TECHNICAL UNIVERSITY OF LODZ / Computer Science**
-- Faculty of Electrical, Electronic, Computer and Control Engineering (2001)  
**BSc in Computer Science; speciality: Network Systems.**
_2015 Thesis: “Remote access to a corporate database of an ERP system based on management system Firebird”._

- **FRONT-END WEB UI FRAMEWORKS AND TOOLS
COURSERA**
The Hong Kong University of Science and Technology
June 2016 - _Certificate no. TLY3KL2FFEC4_

- **HTML, CSS AND JAVA SCRIPT 
COURSERA**
The Hong Kong University of Science and Technology
July 2016 _Certificate no. CJ8GBXDQF434_


- RS School JS/FE course.

### Languages
- *Polish*: Native
- *English*: Intermediate (In the range between B1 (INTERMEDIATE) to B2 (UPPER INTERMEDIATE)) according to  ["EFSET"](https://www.efset.org/) )
- *Russian*: Basic reading and understanding.
