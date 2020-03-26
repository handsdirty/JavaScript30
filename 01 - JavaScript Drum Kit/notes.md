# LEARN
key events
play audio
transition, transition end event (also animation end event).

# resources
http://keycode.info

# data attribute data-xxx
It is made-up key which needs "data-" prefix.
```
<audio data-key="83" src="sounds/hihat.wav"></audio>
```

# Back Tick: ``

# ES6 template string.
```
const audio = document.querySelector(`audio[data-key="${e.keyCode}"]`);
```
这行代码，我们专门为 {e.keyCode} 包上了双引号，因为这里是个 `字符串`.

# Transition
```
transition: all .07s ease;
```
