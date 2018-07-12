# how to change

```js
<input
  value={this.state.value}
  onChange={e => {
    this.setState({ value: e.target.value });
  }}
/>
```
