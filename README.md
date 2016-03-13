# intellij-live-templates
JS &amp; React Live templates

## Snippets

cdm
```js
componentDidMount() {
  $END$
}
```
cdu
```js
componentDidUpdate(prevProps, prevState) {
  $END$
}
```
con
```js
constructor(props) {
  super(props)
  this.state = {$end$}
}
```
cps
```js
const { $state$ } = this.props$end$
```
cts
```js
const { $state$ } = this.state$end$
```
cwm
```js
componentWillMount() {
  $END$
}
```
cwr
```js
componentWillReceiveProps(nextProps) {
  $END$
}
```
cwu
```js
componentWillUpdate(nextProps, nextState) {
  $END$
}
```
cwum
```js
componentWillUnmount() {
  $END$
}
```
fdn
```js
ReactDOM.findDOMNode($END$)
```
pt
```js
$START$: React.PropTypes.$END$
```
rc
```js
class $class$ extends React.Component {
  $end$render() {
    return (
      <div />
    );
  }
}

export default $class$
```
spt
```js
static propTypes = {
  $end$
};
```
tss
```js
this.setState({ $END$ })
```
