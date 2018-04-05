This tutorial will help you to learn reactjs component life cycle methods

# Component Life Cycle Methods

```
  componentDidMount(){
    console.log("componentDidMount called here");
  }

  componentWillMount(){
    console.log("componentWillMount called here");
  }

  componentWillReceiveProps(newProps){
    console.log("componentWillReceiveProps called");
  }

  shouldComponentUpdate(newProps, nextState){
    console.log('Called should component Update');
    return true;
  }
  componentWillUpdate(newProps, nextState){
    console.log('Called component Will Update');
  }
  componentDidUpdate(newProps, nextState){
    console.log('Called component Did Update');
  }
  componentWillUnmount(){
    console.log('Called componentWill un mount');
  }
```

See the output in `console.log` to understand what life cycle method is called on load, on click of the button etc.,


