# Wizard Library
A simple and clean UI.
Credit To Wizard
### Setup The Library
```lua
local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wizard"))()
```



### Adding Window
```lua
local Window = Library:NewWindow("Name")
```



### Adding Tab
```lua
local Tab = Window:NewSection("My Tab")
```



### Adding Button
```lua
Tab:CreateButton("Button", function()
print("hello")
end)
```




### Adding Toggle
```lua
Tab:CreateToggle("Toggle", function(value)
print(value)
end)
```




### Adding Slider
```lua
Tab:CreateSlider("Slider", 0, 100, 15, false, function(value)
print(value)
 end)
```





### Adding TextBox
```lua
Tab:CreateTextbox("TextBox", function(text)
  print(text)
end)
```





### Adding Dropdown
```lua
Tab:CreateDropdown("DropDown", {"Hello", "World", "Hello World"}, 2, function(text)
print(text)
end)
```





### Adding ColorPicker
```lua
Tab:CreateColorPicker("Picker", Color3.new(255, 255, 255), function(value)
print(value)
end)
```




### Credits : Wizard  https://youtube.com/@risedude
