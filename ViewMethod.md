UpdateAnimation();
DrawArena(...);
AddPlayer(tag);
RemovePlayer(tag);
AddDrop(tag);
RemoveDrop(tag);
AddArrow(tag);
RemoveArrow(tag);
NewGame();
vector2D GiveMeAngle(x, y);//координаты точки на экране. и вернуть, куда должен повернутся игрок
Scroll(...);

По факту - во View храним дату для рисования. После всяких дерганий эта дата меняется. Дата - всякие таимера и тд.


Menu. Тут бахнем наследование
Build(name);
Draw(graph);
PickButton(ButtonName);
GetButton(x, y);

Тут наследование. Один класс меню. И все нследуются от него. К примеру, MainMenu
