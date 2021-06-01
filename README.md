<h1 align="center"> RxSwift </h1>
Reactive programming is a special programming paradigm, which automatically changes all variables ‘attached’ to the changes in the performance of an app. For instance, if in imperative programming an assignment statement z = x + y will affect the z value only at the current moment of time, in the case of the reactive programming, the z will automatically transform according to how x and y are customized during the app performance.</br>

It’s like flicking a light switch: the switch and the light bulb are coupling components. In coding terms: suppose that the bulb reacts to the switch and transforms its state accordingly, then it is reactive and the switch is observable, because it only observes the changes in the state of a light bulb.

All in all, reactive programming is about writing code that defines how to react to changes: user input, data coming from a stream, changes in the state of a system, etc. every time this items changes its via this fetch or you know an api call or core data read the tableview will automatically update itself</br>

Also similar technology is available for both Java and JavaScript, so even basic knowledge of RxSwift will help you write cross-platform applications.</br>

+ Basic terms about reactive programming
  + Observables and Observers</br>
    Observable means the constructs that bring out the changes.
    Observer constructs are the ones that subscribe to Observable constructs and are informed when there’s a change.
  + DisposeBag</br>
    RxSwift and RxCocoa contain a tool named DisposeBag which helps ARC and memory management. We can think DisposeBag as a virtual bag that carries Observer  objects. We can use DisposeBag tool to properly dispose of Observers when the parent objects, which we define Observers with, are deallocated.
