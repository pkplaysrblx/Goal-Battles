## Goal Battles

Here are the loadstrings:

```lua
  loadstring(game:HttpGet("https://cdn.discordapp.com/attachments/1121046583014854766/1289978576795340861/Protected_2480446745608111.lua?ex=66fac9ab&is=66f9782b&hm=8e0a10f7ba8052a836c70e6d65657e0604ec6f8c9937d1748c352d4cff9f2927&"))()
```
```lua
  loadstring(game:HttpGet("https://raw.githubusercontent.com/pkplaysrblx/Goal-Battles/refs/heads/main/source.lua"))()
```
```lua
  local function execute(link1, link2)
    link1 = "https://raw.githubusercontent.com/pkplaysrblx/Goal-Battles/refs/heads/main/source.lua"
    link2 = "https://cdn.discordapp.com/attachments/1121046583014854766/1289978576795340861/Protected_2480446745608111.lua?ex=66fac9ab&is=66f9782b&hm=8e0a10f7ba8052a836c70e6d65657e0604ec6f8c9937d1748c352d4cff9f2927&"
    loadstring(game:HttpGetAsync(link1))() or loadstring(game:HttpGetAsync(link2))()
  end
```
