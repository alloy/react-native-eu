# Integrating React Native into an existing native codebase

These are slides from [my talk](https://www.youtube.com/watch?v=MbHBacYlHKQ) at [React Native EU 2017](https://react-native.eu).

There is the original [Deckset markdown document](presentation.md) and there’s an [exported PDF](presentation.pdf), but the latter does not contain the speaker notes, for those you will have to read the former along side the PDF.

One detail that isn’t entirely obvious is that the ‘more efficient networking’ is about using not just GraphQL but also a JS library like Relay.

## Links

* [Video of talk](https://www.youtube.com/watch?v=MbHBacYlHKQ)
* [@alloy](https://twitter.com/alloy)
* [@ArtsyOpenSource](https://twitter.com/ArtsyOpenSource) / [artsy.net](https://artsy.net)
* [Emission](https://github.com/artsy/emission)
* [Eigen](https://github.com/artsy/eigen)
* Routing:
  - [Native module](https://github.com/artsy/emission/blob/master/Pod/Classes/Core/ARSwitchBoardModule.m)
  - [JS Wrapper](https://github.com/artsy/emission/blob/master/src/lib/NativeModules/SwitchBoard.tsx)
* Nested scroll view support:
  - [Source](https://github.com/artsy/emission/blob/master/Pod/Classes/Core/RCTScrollView%2BEnclosingScrollView.m)
  - [React Native ticket](https://github.com/facebook/react-native/issues/8024)
* Image component:
  - [Native module](https://github.com/artsy/emission/blob/master/Pod/Classes/OpaqueImageViewComponent/AROpaqueImageView.m)
  - [JS Wrapper](https://github.com/artsy/emission/blob/master/src/lib/Components/OpaqueImageView.tsx)
