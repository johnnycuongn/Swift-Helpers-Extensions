# Helpers & Extension


### Alertable
Display simple alert message on View Controller

``` Swift 
class ViewController: UIViewController, Alertable {
    
    func showError(_ error: String) {
	// By conforming to Alertable, you have showAlert(message:) function
        showAlert(message: error)
    }
    
}
```
Implement: [Alertable](https://github.com/johnnycuongn/Swift-Helpers-Extensions/tree/main/Alertable)

### Observable
Data Binding 
Implement: [Observable](https://github.com/johnnycuongn/Swift-Helpers-Extensions/tree/main/Observable)

