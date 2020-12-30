# CruzNadin Multi Select 


## ⚡ Npm Commands

Talk to us about more commands if you need

![visitors](https://visitor-badge.glitch.me/badge?page_id=react-native-cn-buttonselect.CruzNadin)

⚡ **Install**
  
```bash
npm i react-native-cn-buttonselect
```
or
```bash
yarn add react-native-cn-buttonselect
```

![android](https://github.com/CruzNadin/react-native-cn-buttonselect/blob/main/screen_1.png)
![ios](https://github.com/CruzNadin/react-native-cn-buttonselect/blob/main/screen_1.png)

⚡ **Usage**
  
```javascript

import SelectBtn from "react-native-cn-buttonselect";

  render(){
    return (
       <SelectBtn 
            data={{title: "Select 1", subtitle: "Select 1 subtitle"}} 
            selectedBtn={(e) => console.log(e)} 
            onPressBtn={() => alert("Click")}
            animationTypes={['rotate']}
            initial={1}
            icon={
                <Icon
                name="check-circle"
                size={25}
                color="#2c9dd1"
                />
            }
        />
    )
  }
}
```
⚡ **Properties**

| Prop  | Description | Default |
| ------------- | ------------- | ------------- |
| data  | radio buttons label array, you can use any data in object, label is necessary for showing in radio button | [] |
| selectedBtn  | callback when radio button clicked | - |
| onPressBtn  | callback when box button clicked | - |
| icon  | you can use any icon for button, see the example | - |
| box  | box of for items  | true |
| initial  | This is used when this component is enabled use only 1. | 0 |
| animationTypes  | the animations when click on item, Valid values: 'zoomIn', 'pulse', 'shake', 'rotate', you can use one or more of this value for exaple: ['pulse'] or ['pulse', 'rotate']  | [] |
| duration  | For how long the animation will run (milliseconds) | 500 |
| style  | style for all RadioButtonRN  | {} |
| boxStyle  | style for box  | {} |
| textStyle  | style for label text  | {} |
| circleSize  | circle size for unselected items and whitout icon selected size | 18 |
| activeColor  | color of active button and box border  | '#03a9f4' |
| deactiveColor  | color of deactive button  | '#e2e2e2' |
| boxActiveBgColor  | background color of active item, when box is true | '#e1f5fe33' |
| boxDeactiveBgColor  | background color of deactive items, when box is true  | '#fff' |
| textColor  | label color  | '#383838' |

## 📫 Contact Us

- Email - [info@tulparyazilim.com.tr](mailto:info@tulparyazilim.com.tr)
- LinkedIn - [Tulpar Yazılım](https://www.linkedin.com/company/tulparyazilim)
- Blog - [Blog](https://www.tulparyazilim.com.tr/blog)

---

<img src="https://www.tulparyazilim.com.tr/img/logo.png" />

⭐️ From [Tulpar Yazılım](https://github.com/tulparyazilim)
