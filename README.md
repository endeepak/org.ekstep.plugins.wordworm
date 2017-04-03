# WordWorm

Plugin to teach word spellings - Inspired by [snake game](https://en.wikipedia.org/wiki/Snake_(video_game))

> Less known fact : Every book worm starts as a word worm

#### Features

* Detects successful word formation
* Detects wrong order of alphabets as soon as alphabet is eaten by the worm
* Detects wall collision
* Detects worm collision to its own body

### Demo

[![Video : Successful word formation](https://img.youtube.com/vi/IMmz9cRKv9I/0.jpg)](https://www.youtube.com/watch?v=IMmz9cRKv9I)


### How to run

```
mkdir esktep-plugins && cd esktep-plugins
git clone https://github.com/endeepak/org.ekstep.plugins.wordworm.git org.ekstep.plugins.wordworm-1.0
npm install -g https://github.com/ekstep/EkStep-Content-SDK.git
ekstep-content-sdk serve
```

Follow the instructions : https://github.com/ekstep/Contributed-Plugins/wiki/Using-SDK-to-create-and-test-plugin#enable-ssl-access-for-localhost

### Limitations

Currently the navigation is based on keyboard navigation keys `UP`, `DOWN`, `LEFT`, `RIGHT`. This needs to be changed to on screen navigation buttons to make it usable on mobile device

### TODO

- [ ] Add on screen control for worm navigation so it can used on mobile device
- [ ] Use an image for worm head to make it look like a worm
- [ ] Show word or image of the word that should be formed by the worm
- [ ] Show on screen success and failure message
- [ ] Make it work like an assessment (Blocker: There are no docs on how to do this)