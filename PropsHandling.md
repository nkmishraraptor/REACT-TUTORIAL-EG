REACT PROPS:
Arguments passed into React components,passed to components via HTML attributes,ike function arguments in JavaScript and attributes in HTML.

EG:
Add a "brand" attribute to the FirstProps element:
const myelement6=<FirstProps brand="Ford" />;
The component receives the argument as a props object:
EXAMPLE:
Use the brand attribute in the component:
index.js:
class FirstProps extends React.Component 
{
 render() 
 {
  return <h2>This is one of brand of raptor - {this.props.brand}!</h2>
 }
}    
const myelement6=<FirstProps brand="McMaster" />;
ReactDOM.render(myelement6,document.getElementById('props_ele'));
html:
<div id="props_ele"></div> 
