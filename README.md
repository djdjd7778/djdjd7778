## Hi there 👋


```lua

local name = "djdjd7778(by チーパー君)"
local age = "非公開"
local hobbies = {"睡眠"}
local favorite_food = {"ラーメン,"パフェ","アイス"}
local location = "日本"
local skills = {"Lua"}

-- 自己紹介関数
local function introduce()
    print("名前: " .. name)
    print("年齢: " .. age)
    print("趣味: " .. table.concat(hobbies, ", "))
    print("好きな食べ物: " .. table.concat(favorite_food, ", "))
    print("住んでいる場所: " .. location)
    print("スキル: " .. table.concat(skills, ", "))
end

introduce()
