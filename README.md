# Colorized-for-Love
this library for lua help to load a array of r[1], g[2], b[3], a[4] for implement colors in your project
an examle:
````lua
  require("colorized")
  love.draw()
    love.graphics.setBackgroundColor(hex("#fff")) --this will go turn the background into white and 1 of alpha
    love.graphics.setColor(rgba(255, 140, 10)) --a type of orange i think
    love.graphics.setColor(vec4(0, 0, 50, 0.5)) --dark blue with parcial alpha
    love.graphics.setColor(hex("#a2f5a1")) --i dont know ;D
  end
````

Basic colors :
color.blue
color.cyan 

Example :
```lua
require("colorize")
function love.draw()
  love.graphics.setColor(color.cyan)
  love.graphics.rectangle("fill", 100, 100, 200, 100)

  love.graphics.setColor(color.orange)
  love.graphics.circle("fill", 400, 200, 50)

  love.graphics.setColor(color.purple)
  love.graphics.print("Hello Colors!", 100, 300)
end

```

future implementations:
  -hsva
  -hsla
