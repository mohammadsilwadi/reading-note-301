# React Docs - Forms

## What is a ‘Controlled Component’?

A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why

the displayed value will update as the user types.

## How do we target what the user is entering if we have an event handler on an input field?

  handleChange(event) {    this.setState({value: event.target.value});  }

  input type="text" value={this.state.value} onChange={this.handleChange}
    input type="submit" value="Submit"

# The Conditional (Ternary) Operator Explained

## Why would we use a ternary operator?

Programmers use the ternary operator for decision making in place of longer if and else conditional statements.

## Rewrite the following statement using a ternary statement

  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
x===y ?  console.log(true); :console.log(false)
