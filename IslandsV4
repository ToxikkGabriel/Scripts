print("Script Source Released on 17.03.2024 (DD/MM/YYYY because Islands is Dead!")
warn("THIS SCRIPT IS DISCONTINUED FROM NOW!")
for i = 1, 50 do
  print("Nekohub on Top | discord.gg/MbsxuDEzgT")
end
-- This is a pretty old script, so don’t joke about the source – it’s older than 90% of the Roblox community. -- 

repeat wait() until game:IsLoaded()

local IsPremium = true 
local DidKey = false
local ScriptVersion = "V4"

local FileName = "Nekohub"
local GameName = "Islands"
local DeveloperVersion = true

local NotificationIcon = "rbxassetid://1234567890"

function SendNotification(Title, Text)
	game:GetService("StarterGui"):SetCore("SendNotification",{
		Title = Title, -- Required
		Text = Text, -- Required
		Icon = NotificationIcon -- Optional
	})
end	

SendNotification("Welcome!", "Welcome to "..FileName .. " " .. ScriptVersion.."!")

local PremiumText1 = "Premium is only 2$ Lifetime. Go buy it in discord.gg/MbsxuDEzgT"

if isfolder(FileName) then

else
	makefolder(FileName)
end


if isfolder(FileName.."/"..GameName) then

else
	makefolder(FileName.."/"..GameName)
end

function IsFile(Name)
	return isfile(FileName.."/"..GameName.."/"..Name)
end	

function IsFolder(Name)
	return isfolder(FileName.."/"..GameName.."/"..Name)
end	


function ReadFile(Name) 
	if isfile(FileName.."/"..GameName.."/"..Name) == true then
		return readfile(FileName.."/"..GameName.."/"..Name)
	else
		return readfile(FileName.."/"..GameName..Name)
	end
	return readfile(FileName.."/"..GameName.."/"..Name)
end

function CreateFolder(Name)
	makefolder(FileName.."/"..GameName.."/"..Name)
end	

function CreateFile(Name, Data, CheckIfFile)
	if CheckIfFile == true then
		if isfile(FileName.."/"..GameName.."/"..Name) then

		else
			writefile(FileName.."/"..GameName.."/"..Name, Data)
		end
	else
		writefile(FileName.."/"..GameName.."/"..Name, Data)
	end
end	

task.wait(1)

function GetSchematicaFiles()
	local Path = FileName.."/"..GameName.."/".."Schematica"

	local Files = listfiles(Path)

	if not Files or (#Files == 0) then
		local TemplateFile = game:HttpGet("https://pastebin.com/raw/yQUgfbZy")
		CreateFile("/Schematica/Template", TemplateFile, false)

		task.wait(1)

		local Files = listfiles(Path)

		return Files;

	else
		return Files;
	end

end

CreateFolder("Schematica")

CreateFolder("ello")

if IsPremium == false then -- true
	IsPremium = true
	DidKey = true
else
	DidKey = false
end


local CloneFolder

if game:GetService("Workspace"):FindFirstChild("Clones/Ne_KO_HUB") then
	CloneFolder = game:GetService("Workspace"):FindFirstChild("Clones/Ne_KO_HUB")
else
	local F = Instance.new("Model")
	F.Parent = game:GetService("Workspace")
	F.Name = "Clones/Ne_KO_HUB"
	CloneFolder = F
end

function DeleteIsland(PASSWORD)
	if PASSWORD == "UI NB)QUN BGTUI(O $ I)ONHZIO$NUI GOH)U$UB GZ)($NZOU IGHN$)(TMI)(O)" then 
		game:GetService("ReplicatedStorage"):WaitForChild("rbxts_include"):WaitForChild("node_modules"):WaitForChild("@rbxts"):WaitForChild("net"):WaitForChild("out"):WaitForChild("_NetManaged"):WaitForChild("CLIENT_RESET_ISLAND_REQUEST"):InvokeServer()
	end
end

function IsInTable(Table, NameToCheck)
	if NameToCheck and Table then
		if type(Table) == "table" then
			if table.find(Table, NameToCheck) then
				return true
			else
				return false
			end
		else
			if type(Table) == "string" then
				if Table == NameToCheck then
					return true
				else
					return false
				end
			end
		end
	else
		return false
	end
end

function DebugCheck(N,Text)
	if _G.DebugMode == true then
		rconsolename("Debug")
		if N == nil then
			N = 0
		end 
		if N == 0 then
			rconsoleprint("\n"..Text)
		end
	end
end

DebugCheck(0,"im waiting...")

local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
	vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
	wait(1)
	vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
wait(1)
local NofLiberyLocal = [[
local Release = "Beta 8"
local NotificationDuration = 6.5
local RayfieldFolder = "Rayfield"
local ConfigurationFolder = RayfieldFolder.."/Configurations"
local ConfigurationExtension = ".rfld"



local RayfieldLibrary = {
	Flags = {},
	Theme = {
		Default = {
			TextFont = "Default", -- Default will use the various font faces used across Rayfield
			TextColor = Color3.fromRGB(240, 240, 240),

			Background = Color3.fromRGB(25, 25, 25),
			Topbar = Color3.fromRGB(34, 34, 34),
			Shadow = Color3.fromRGB(20, 20, 20),

			NotificationBackground = Color3.fromRGB(20, 20, 20),
			NotificationActionsBackground = Color3.fromRGB(230, 230, 230),

			TabBackground = Color3.fromRGB(80, 80, 80),
			TabStroke = Color3.fromRGB(85, 85, 85),
			TabBackgroundSelected = Color3.fromRGB(210, 210, 210),
			TabTextColor = Color3.fromRGB(240, 240, 240),
			SelectedTabTextColor = Color3.fromRGB(50, 50, 50),

			ElementBackground = Color3.fromRGB(35, 35, 35),
			ElementBackgroundHover = Color3.fromRGB(40, 40, 40),
			SecondaryElementBackground = Color3.fromRGB(25, 25, 25), -- For labels and paragraphs
			ElementStroke = Color3.fromRGB(50, 50, 50),
			SecondaryElementStroke = Color3.fromRGB(40, 40, 40), -- For labels and paragraphs

			SliderBackground = Color3.fromRGB(43, 105, 159),
			SliderProgress = Color3.fromRGB(43, 105, 159),
			SliderStroke = Color3.fromRGB(48, 119, 177),

			ToggleBackground = Color3.fromRGB(30, 30, 30),
			ToggleEnabled = Color3.fromRGB(0, 146, 214),
			ToggleDisabled = Color3.fromRGB(100, 100, 100),
			ToggleEnabledStroke = Color3.fromRGB(0, 170, 255),
			ToggleDisabledStroke = Color3.fromRGB(125, 125, 125),
			ToggleEnabledOuterStroke = Color3.fromRGB(100, 100, 100),
			ToggleDisabledOuterStroke = Color3.fromRGB(65, 65, 65),

			InputBackground = Color3.fromRGB(30, 30, 30),
			InputStroke = Color3.fromRGB(65, 65, 65),
			PlaceholderColor = Color3.fromRGB(178, 178, 178)
		},
		Light = {
			TextFont = "Gotham", -- Default will use the various font faces used across Rayfield
			TextColor = Color3.fromRGB(50, 50, 50), -- i need to make all text 240, 240, 240 and base gray on transparency not color to do this

			Background = Color3.fromRGB(255, 255, 255),
			Topbar = Color3.fromRGB(217, 217, 217),
			Shadow = Color3.fromRGB(223, 223, 223),

			NotificationBackground = Color3.fromRGB(20, 20, 20),
			NotificationActionsBackground = Color3.fromRGB(230, 230, 230),

			TabBackground = Color3.fromRGB(220, 220, 220),
			TabStroke = Color3.fromRGB(112, 112, 112),
			TabBackgroundSelected = Color3.fromRGB(0, 142, 208),
			TabTextColor = Color3.fromRGB(240, 240, 240),
			SelectedTabTextColor = Color3.fromRGB(50, 50, 50),

			ElementBackground = Color3.fromRGB(198, 198, 198),
			ElementBackgroundHover = Color3.fromRGB(230, 230, 230),
			SecondaryElementBackground = Color3.fromRGB(136, 136, 136), -- For labels and paragraphs
			ElementStroke = Color3.fromRGB(180, 199, 97),
			SecondaryElementStroke = Color3.fromRGB(40, 40, 40), -- For labels and paragraphs

			SliderBackground = Color3.fromRGB(31, 159, 71),
			SliderProgress = Color3.fromRGB(31, 159, 71),
			SliderStroke = Color3.fromRGB(42, 216, 94),

			ToggleBackground = Color3.fromRGB(170, 203, 60),
			ToggleEnabled = Color3.fromRGB(32, 214, 29),
			ToggleDisabled = Color3.fromRGB(100, 22, 23),
			ToggleEnabledStroke = Color3.fromRGB(17, 255, 0),
			ToggleDisabledStroke = Color3.fromRGB(65, 8, 8),
			ToggleEnabledOuterStroke = Color3.fromRGB(0, 170, 0),
			ToggleDisabledOuterStroke = Color3.fromRGB(170, 0, 0),

			InputBackground = Color3.fromRGB(31, 159, 71),
			InputStroke = Color3.fromRGB(19, 65, 31),
			PlaceholderColor = Color3.fromRGB(178, 178, 178)
		}
	}
}



-- Services

local UserInputService = game:GetService("UserInputService")
local TweenService = game:GetService("TweenService")
local HttpService = game:GetService("HttpService")
local RunService = game:GetService("RunService")
local Players = game:GetService("Players")
local CoreGui = game:GetService("CoreGui")

-- Interface Management
local Rayfield = game:GetObjects("rbxassetid://10804731440")[1]

Rayfield.Enabled = false


if gethui then
	Rayfield.Parent = gethui()
elseif syn.protect_gui then 
	syn.protect_gui(Rayfield)
	Rayfield.Parent = CoreGui
elseif CoreGui:FindFirstChild("RobloxGui") then
	Rayfield.Parent = CoreGui:FindFirstChild("RobloxGui")
else
	Rayfield.Parent = CoreGui
end

if gethui then
	for _, Interface in ipairs(gethui():GetChildren()) do
		if Interface.Name == Rayfield.Name and Interface ~= Rayfield then
			Interface.Enabled = false
			Interface.Name = "Rayfield-Old"
		end
	end
else
	for _, Interface in ipairs(CoreGui:GetChildren()) do
		if Interface.Name == Rayfield.Name and Interface ~= Rayfield then
			Interface.Enabled = false
			Interface.Name = "Rayfield-Old"
		end
	end
end

-- Object Variables

local Camera = workspace.CurrentCamera
local Main = Rayfield.Main
local Topbar = Main.Topbar
local Elements = Main.Elements
local LoadingFrame = Main.LoadingFrame
local TabList = Main.TabList

Rayfield.DisplayOrder = 100
LoadingFrame.Version.Text = Release


-- Variables

local request = (syn and syn.request) or (http and http.request) or http_request
local CFileName = nil
local CEnabled = false
local Minimised = false
local Hidden = false
local Debounce = false
local Notifications = Rayfield.Notifications

local SelectedTheme = RayfieldLibrary.Theme.Default

function ChangeTheme(ThemeName)
	SelectedTheme = RayfieldLibrary.Theme[ThemeName]
	for _, obj in ipairs(Rayfield:GetDescendants()) do
		if obj.ClassName == "TextLabel" or obj.ClassName == "TextBox" or obj.ClassName == "TextButton" then
			if SelectedTheme.TextFont ~= "Default" then 
				obj.TextColor3 = SelectedTheme.TextColor
				obj.Font = SelectedTheme.TextFont
			end
		end
	end

	Rayfield.Main.BackgroundColor3 = SelectedTheme.Background
	Rayfield.Main.Topbar.BackgroundColor3 = SelectedTheme.Topbar
	Rayfield.Main.Topbar.CornerRepair.BackgroundColor3 = SelectedTheme.Topbar
	Rayfield.Main.Shadow.Image.ImageColor3 = SelectedTheme.Shadow

	Rayfield.Main.Topbar.ChangeSize.ImageColor3 = SelectedTheme.TextColor
	Rayfield.Main.Topbar.Hide.ImageColor3 = SelectedTheme.TextColor
	Rayfield.Main.Topbar.Theme.ImageColor3 = SelectedTheme.TextColor

	for _, TabPage in ipairs(Elements:GetChildren()) do
		for _, Element in ipairs(TabPage:GetChildren()) do
			if Element.ClassName == "Frame" and Element.Name ~= "Placeholder" and Element.Name ~= "SectionSpacing" and Element.Name ~= "SectionTitle"  then
				Element.BackgroundColor3 = SelectedTheme.ElementBackground
				Element.UIStroke.Color = SelectedTheme.ElementStroke
			end
		end
	end

end

local function AddDraggingFunctionality(DragPoint, Main)
	pcall(function()
		local Dragging, DragInput, MousePos, FramePos = false
		DragPoint.InputBegan:Connect(function(Input)
			if Input.UserInputType == Enum.UserInputType.MouseButton1 then
				Dragging = true
				MousePos = Input.Position
				FramePos = Main.Position

				Input.Changed:Connect(function()
					if Input.UserInputState == Enum.UserInputState.End then
						Dragging = false
					end
				end)
			end
		end)
		DragPoint.InputChanged:Connect(function(Input)
			if Input.UserInputType == Enum.UserInputType.MouseMovement then
				DragInput = Input
			end
		end)
		UserInputService.InputChanged:Connect(function(Input)
			if Input == DragInput and Dragging then
				local Delta = Input.Position - MousePos
				TweenService:Create(Main, TweenInfo.new(0.45, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Position  = UDim2.new(FramePos.X.Scale,FramePos.X.Offset + Delta.X, FramePos.Y.Scale, FramePos.Y.Offset + Delta.Y)}):Play()
			end
		end)
	end)
end   

local function PackColor(Color)
	return {R = Color.R * 255, G = Color.G * 255, B = Color.B * 255}
end    

local function UnpackColor(Color)
	return Color3.fromRGB(Color.R, Color.G, Color.B)
end

local function LoadConfiguration(Configuration)
	local Data = HttpService:JSONDecode(Configuration)
	for FlagName, FlagValue in next, Data do
		if RayfieldLibrary.Flags[FlagName] then
			spawn(function() 
				if RayfieldLibrary.Flags[FlagName].Type == "ColorPicker" then
					RayfieldLibrary.Flags[FlagName]:Set(UnpackColor(FlagValue))
				else
					if RayfieldLibrary.Flags[FlagName].CurrentValue or RayfieldLibrary.Flags[FlagName].CurrentKeybind or RayfieldLibrary.Flags[FlagName].CurrentOption or RayfieldLibrary.Flags[FlagName].Color ~= FlagValue then RayfieldLibrary.Flags[FlagName]:Set(FlagValue) end
				end    
			end)
		else
			RayfieldLibrary:Notify({Title = "Flag Error", Content = "Rayfield was unable to find '"..FlagName.. "'' in the current script"})
		end
	end
end

local function SaveConfiguration()
	if not CEnabled then return end
	local Data = {}
	for i,v in pairs(RayfieldLibrary.Flags) do
		if v.Type == "ColorPicker" then
			Data[i] = PackColor(v.Color)
		else
			Data[i] = v.CurrentValue or v.CurrentKeybind or v.CurrentOption or v.Color
		end
	end	
	writefile(ConfigurationFolder .. "/" .. CFileName .. ConfigurationExtension, tostring(HttpService:JSONEncode(Data)))
end

local neon = (function() -- Open sourced neon module
	local module = {}

	do
		local function IsNotNaN(x)
			return x == x
		end
		local continued = IsNotNaN(Camera:ScreenPointToRay(0,0).Origin.x)
		while not continued do
			RunService.RenderStepped:wait()
			continued = IsNotNaN(Camera:ScreenPointToRay(0,0).Origin.x)
		end
	end
	local RootParent = Camera
	if getgenv().SecureMode == nil then
		RootParent = Camera
	else
		if not getgenv().SecureMode then
			RootParent = Camera
		else 
			RootParent = nil
		end
	end


	local binds = {}
	local root = Instance.new('Folder', RootParent)
	root.Name = 'neon'


	local GenUid; do
		local id = 0
		function GenUid()
			id = id + 1
			return 'neon::'..tostring(id)
		end
	end

	local DrawQuad; do
		local acos, max, pi, sqrt = math.acos, math.max, math.pi, math.sqrt
		local sz = 0.2

		function DrawTriangle(v1, v2, v3, p0, p1)
			local s1 = (v1 - v2).magnitude
			local s2 = (v2 - v3).magnitude
			local s3 = (v3 - v1).magnitude
			local smax = max(s1, s2, s3)
			local A, B, C
			if s1 == smax then
				A, B, C = v1, v2, v3
			elseif s2 == smax then
				A, B, C = v2, v3, v1
			elseif s3 == smax then
				A, B, C = v3, v1, v2
			end

			local para = ( (B-A).x*(C-A).x + (B-A).y*(C-A).y + (B-A).z*(C-A).z ) / (A-B).magnitude
			local perp = sqrt((C-A).magnitude^2 - para*para)
			local dif_para = (A - B).magnitude - para

			local st = CFrame.new(B, A)
			local za = CFrame.Angles(pi/2,0,0)

			local cf0 = st

			local Top_Look = (cf0 * za).lookVector
			local Mid_Point = A + CFrame.new(A, B).LookVector * para
			local Needed_Look = CFrame.new(Mid_Point, C).LookVector
			local dot = Top_Look.x*Needed_Look.x + Top_Look.y*Needed_Look.y + Top_Look.z*Needed_Look.z

			local ac = CFrame.Angles(0, 0, acos(dot))

			cf0 = cf0 * ac
			if ((cf0 * za).lookVector - Needed_Look).magnitude > 0.01 then
				cf0 = cf0 * CFrame.Angles(0, 0, -2*acos(dot))
			end
			cf0 = cf0 * CFrame.new(0, perp/2, -(dif_para + para/2))

			local cf1 = st * ac * CFrame.Angles(0, pi, 0)
			if ((cf1 * za).lookVector - Needed_Look).magnitude > 0.01 then
				cf1 = cf1 * CFrame.Angles(0, 0, 2*acos(dot))
			end
			cf1 = cf1 * CFrame.new(0, perp/2, dif_para/2)

			if not p0 then
				p0 = Instance.new('Part')
				p0.FormFactor = 'Custom'
				p0.TopSurface = 0
				p0.BottomSurface = 0
				p0.Anchored = true
				p0.CanCollide = false
				p0.Material = 'Glass'
				p0.Size = Vector3.new(sz, sz, sz)
				local mesh = Instance.new('SpecialMesh', p0)
				mesh.MeshType = 2
				mesh.Name = 'WedgeMesh'
			end
			p0.WedgeMesh.Scale = Vector3.new(0, perp/sz, para/sz)
			p0.CFrame = cf0

			if not p1 then
				p1 = p0:clone()
			end
			p1.WedgeMesh.Scale = Vector3.new(0, perp/sz, dif_para/sz)
			p1.CFrame = cf1

			return p0, p1
		end

		function DrawQuad(v1, v2, v3, v4, parts)
			parts[1], parts[2] = DrawTriangle(v1, v2, v3, parts[1], parts[2])
			parts[3], parts[4] = DrawTriangle(v3, v2, v4, parts[3], parts[4])
		end
	end

	function module:BindFrame(frame, properties)
		if RootParent == nil then return end
		if binds[frame] then
			return binds[frame].parts
		end

		local uid = GenUid()
		local parts = {}
		local f = Instance.new('Folder', root)
		f.Name = frame.Name

		local parents = {}
		do
			local function add(child)
				if child:IsA'GuiObject' then
					parents[#parents + 1] = child
					add(child.Parent)
				end
			end
			add(frame)
		end

		local function UpdateOrientation(fetchProps)
			local zIndex = 1 - 0.05*frame.ZIndex
			local tl, br = frame.AbsolutePosition, frame.AbsolutePosition + frame.AbsoluteSize
			local tr, bl = Vector2.new(br.x, tl.y), Vector2.new(tl.x, br.y)
			do
				local rot = 0;
				for _, v in ipairs(parents) do
					rot = rot + v.Rotation
				end
				if rot ~= 0 and rot%180 ~= 0 then
					local mid = tl:lerp(br, 0.5)
					local s, c = math.sin(math.rad(rot)), math.cos(math.rad(rot))
					local vec = tl
					tl = Vector2.new(c*(tl.x - mid.x) - s*(tl.y - mid.y), s*(tl.x - mid.x) + c*(tl.y - mid.y)) + mid
					tr = Vector2.new(c*(tr.x - mid.x) - s*(tr.y - mid.y), s*(tr.x - mid.x) + c*(tr.y - mid.y)) + mid
					bl = Vector2.new(c*(bl.x - mid.x) - s*(bl.y - mid.y), s*(bl.x - mid.x) + c*(bl.y - mid.y)) + mid
					br = Vector2.new(c*(br.x - mid.x) - s*(br.y - mid.y), s*(br.x - mid.x) + c*(br.y - mid.y)) + mid
				end
			end
			DrawQuad(
				Camera:ScreenPointToRay(tl.x, tl.y, zIndex).Origin, 
				Camera:ScreenPointToRay(tr.x, tr.y, zIndex).Origin, 
				Camera:ScreenPointToRay(bl.x, bl.y, zIndex).Origin, 
				Camera:ScreenPointToRay(br.x, br.y, zIndex).Origin, 
				parts
			)
			if fetchProps then
				for _, pt in pairs(parts) do
					pt.Parent = f
				end
				for propName, propValue in pairs(properties) do
					for _, pt in pairs(parts) do
						pt[propName] = propValue
					end
				end
			end
		end

		UpdateOrientation(true)
		RunService:BindToRenderStep(uid, 2000, UpdateOrientation)

		binds[frame] = {
			uid = uid;
			parts = parts;
		}
		return binds[frame].parts
	end

	function module:Modify(frame, properties)
		local parts = module:GetBoundParts(frame)
		if parts then
			for propName, propValue in pairs(properties) do
				for _, pt in pairs(parts) do
					pt[propName] = propValue
				end
			end
		end
	end

	function module:UnbindFrame(frame)
		if RootParent == nil then return end
		local cb = binds[frame]
		if cb then
			RunService:UnbindFromRenderStep(cb.uid)
			for _, v in pairs(cb.parts) do
				v:Destroy()
			end
			binds[frame] = nil
		end
	end

	function module:HasBinding(frame)
		return binds[frame] ~= nil
	end

	function module:GetBoundParts(frame)
		return binds[frame] and binds[frame].parts
	end


	return module

end)()

function RayfieldLibrary:Notify(NotificationSettings)
	spawn(function()
		local ActionCompleted = true
		local Notification = Notifications.Template:Clone()
		Notification.Parent = Notifications
		Notification.Name = NotificationSettings.Title or "Unknown Title"
		Notification.Visible = true

		local blurlight = nil
		if not getgenv().SecureMode then
			blurlight = Instance.new("DepthOfFieldEffect",game:GetService("Lighting"))
			blurlight.Enabled = true
			blurlight.FarIntensity = 0
			blurlight.FocusDistance = 51.6
			blurlight.InFocusRadius = 50
			blurlight.NearIntensity = 1
			game:GetService("Debris"):AddItem(script,0)
		end

		Notification.Actions.Template.Visible = false

		if NotificationSettings.Actions then
			for _, Action in pairs(NotificationSettings.Actions) do
				ActionCompleted = false
				local NewAction = Notification.Actions.Template:Clone()
				NewAction.BackgroundColor3 = SelectedTheme.NotificationActionsBackground
				if SelectedTheme ~= RayfieldLibrary.Theme.Default then
					NewAction.TextColor3 = SelectedTheme.TextColor
				end
				NewAction.Name = Action.Name
				NewAction.Visible = true
				NewAction.Parent = Notification.Actions
				NewAction.Text = Action.Name
				NewAction.BackgroundTransparency = 1
				NewAction.TextTransparency = 1
				NewAction.Size = UDim2.new(0, NewAction.TextBounds.X + 27, 0, 36)

				NewAction.MouseButton1Click:Connect(function()
					local Success, Response = pcall(Action.Callback)
					if not Success then
						print("Rayfield | Action: "..Action.Name.." Callback Error " ..tostring(Response))
					end
					ActionCompleted = true
				end)
			end
		end
		Notification.BackgroundColor3 = SelectedTheme.Background
		Notification.Title.Text = NotificationSettings.Title or "Unknown"
		Notification.Title.TextTransparency = 1
		Notification.Title.TextColor3 = SelectedTheme.TextColor
		Notification.Description.Text = NotificationSettings.Content or "Unknown"
		Notification.Description.TextTransparency = 1
		Notification.Description.TextColor3 = SelectedTheme.TextColor
		Notification.Icon.ImageColor3 = SelectedTheme.TextColor
		if NotificationSettings.Image then
			Notification.Icon.Image = "rbxassetid://"..tostring(NotificationSettings.Image) 
		else
			Notification.Icon.Image = "rbxassetid://3944680095"
		end

		Notification.Icon.ImageTransparency = 1

		Notification.Parent = Notifications
		Notification.Size = UDim2.new(0, 260, 0, 80)
		Notification.BackgroundTransparency = 1

		TweenService:Create(Notification, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 295, 0, 91)}):Play()
		TweenService:Create(Notification, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.1}):Play()
		Notification:TweenPosition(UDim2.new(0.5,0,0.915,0),'Out','Quint',0.8,true)

		wait(0.3)
		TweenService:Create(Notification.Icon, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {ImageTransparency = 0}):Play()
		TweenService:Create(Notification.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
		TweenService:Create(Notification.Description, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0.2}):Play()
		wait(0.2)



		-- Requires Graphics Level 8-10
		if getgenv().SecureMode == nil then
			TweenService:Create(Notification, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.4}):Play()
		else
			if not getgenv().SecureMode then
				TweenService:Create(Notification, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.4}):Play()
			else 
				TweenService:Create(Notification, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			end
		end

		if Rayfield.Name == "Rayfield" then
			neon:BindFrame(Notification.BlurModule, {
				Transparency = 0.98;
				BrickColor = BrickColor.new("Institutional white");
			})
		end

		if not NotificationSettings.Actions then
			wait(NotificationSettings.Duration or NotificationDuration - 0.5)
		else
			wait(0.8)
			TweenService:Create(Notification, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 295, 0, 132)}):Play()
			wait(0.3)
			for _, Action in ipairs(Notification.Actions:GetChildren()) do
				if Action.ClassName == "TextButton" and Action.Name ~= "Template" then
					TweenService:Create(Action, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.2}):Play()
					TweenService:Create(Action, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
					wait(0.05)
				end
			end
		end

		repeat wait(0.001) until ActionCompleted

		for _, Action in ipairs(Notification.Actions:GetChildren()) do
			if Action.ClassName == "TextButton" and Action.Name ~= "Template" then
				TweenService:Create(Action, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
				TweenService:Create(Action, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
			end
		end

		TweenService:Create(Notification.Title, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Position = UDim2.new(0.47, 0,0.234, 0)}):Play()
		TweenService:Create(Notification.Description, TweenInfo.new(0.8, Enum.EasingStyle.Quint), {Position = UDim2.new(0.528, 0,0.637, 0)}):Play()
		TweenService:Create(Notification, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 280, 0, 83)}):Play()
		TweenService:Create(Notification.Icon, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
		TweenService:Create(Notification, TweenInfo.new(0.8, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.6}):Play()

		wait(0.3)
		TweenService:Create(Notification.Title, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0.4}):Play()
		TweenService:Create(Notification.Description, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0.5}):Play()
		wait(0.4)
		TweenService:Create(Notification, TweenInfo.new(0.9, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 260, 0, 0)}):Play()
		TweenService:Create(Notification, TweenInfo.new(0.8, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
		TweenService:Create(Notification.Title, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
		TweenService:Create(Notification.Description, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
		wait(0.2)
		if not getgenv().SecureMode then
			neon:UnbindFrame(Notification.BlurModule)
			blurlight:Destroy()
		end
		wait(0.9)
		Notification:Destroy()
	end)
end

function Hide()
	Debounce = true
	RayfieldLibrary:Notify({Title = "Interface Hidden", Content = "The interface has been hidden, you can unhide the interface by tapping K", Duration = 7})
	TweenService:Create(Main, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 470, 0, 400)}):Play()
	TweenService:Create(Main.Topbar, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 470, 0, 45)}):Play()
	TweenService:Create(Main, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
	TweenService:Create(Main.Topbar, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
	TweenService:Create(Main.Topbar.Divider, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
	TweenService:Create(Main.Topbar.CornerRepair, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
	TweenService:Create(Main.Topbar.Title, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
	TweenService:Create(Main.Shadow.Image, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
	TweenService:Create(Topbar.UIStroke, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
	for _, TopbarButton in ipairs(Topbar:GetChildren()) do
		if TopbarButton.ClassName == "ImageButton" then
			TweenService:Create(TopbarButton, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
		end
	end
	for _, tabbtn in ipairs(TabList:GetChildren()) do
		if tabbtn.ClassName == "Frame" and tabbtn.Name ~= "Placeholder" then
			TweenService:Create(tabbtn, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
			TweenService:Create(tabbtn.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
			TweenService:Create(tabbtn.Image, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
			TweenService:Create(tabbtn.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
			TweenService:Create(tabbtn.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
		end
	end
	for _, tab in ipairs(Elements:GetChildren()) do
		if tab.Name ~= "Template" and tab.ClassName == "ScrollingFrame" and tab.Name ~= "Placeholder" then
			for _, element in ipairs(tab:GetChildren()) do
				if element.ClassName == "Frame" then
					if element.Name ~= "SectionSpacing" and element.Name ~= "Placeholder" then
						if element.Name == "SectionTitle" then
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						else
							TweenService:Create(element, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
							TweenService:Create(element.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						end
						for _, child in ipairs(element:GetChildren()) do
							if child.ClassName == "Frame" or child.ClassName == "TextLabel" or child.ClassName == "TextBox" or child.ClassName == "ImageButton" or child.ClassName == "ImageLabel" then
								child.Visible = false
							end
						end
					end
				end
			end
		end
	end
	wait(0.5)
	Main.Visible = false
	Debounce = false
end

function Unhide()
	Debounce = true
	Main.Position = UDim2.new(0.5, 0, 0.5, 0)
	Main.Visible = true
	TweenService:Create(Main, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 500, 0, 475)}):Play()
	TweenService:Create(Main.Topbar, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 500, 0, 45)}):Play()
	TweenService:Create(Main.Shadow.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.4}):Play()
	TweenService:Create(Main, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Main.Topbar, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Main.Topbar.Divider, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Main.Topbar.CornerRepair, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Main.Topbar.Title, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
	if Minimised then
		spawn(Maximise)
	end
	for _, TopbarButton in ipairs(Topbar:GetChildren()) do
		if TopbarButton.ClassName == "ImageButton" then
			TweenService:Create(TopbarButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.8}):Play()
		end
	end
	for _, tabbtn in ipairs(TabList:GetChildren()) do
		if tabbtn.ClassName == "Frame" and tabbtn.Name ~= "Placeholder" then
			if tostring(Elements.UIPageLayout.CurrentPage) == tabbtn.Title.Text then
				TweenService:Create(tabbtn, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
				TweenService:Create(tabbtn.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
				TweenService:Create(tabbtn.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.9}):Play()
				TweenService:Create(tabbtn.Image, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0}):Play()
				TweenService:Create(tabbtn.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
			else
				TweenService:Create(tabbtn, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.7}):Play()
				TweenService:Create(tabbtn.Image, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.2}):Play()
				TweenService:Create(tabbtn.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.7}):Play()
				TweenService:Create(tabbtn.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0.2}):Play()
				TweenService:Create(tabbtn.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			end

		end
	end
	for _, tab in ipairs(Elements:GetChildren()) do
		if tab.Name ~= "Template" and tab.ClassName == "ScrollingFrame" and tab.Name ~= "Placeholder" then
			for _, element in ipairs(tab:GetChildren()) do
				if element.ClassName == "Frame" then
					if element.Name ~= "SectionSpacing" and element.Name ~= "Placeholder" then
						if element.Name == "SectionTitle" then
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
						else
							TweenService:Create(element, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
							TweenService:Create(element.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
						end
						for _, child in ipairs(element:GetChildren()) do
							if child.ClassName == "Frame" or child.ClassName == "TextLabel" or child.ClassName == "TextBox" or child.ClassName == "ImageButton" or child.ClassName == "ImageLabel" then
								child.Visible = true
							end
						end
					end
				end
			end
		end
	end
	wait(0.5)
	Minimised = false
	Debounce = false
end

function Maximise()
	Debounce = true
	Topbar.ChangeSize.Image = "rbxassetid://"..10137941941


	TweenService:Create(Topbar.UIStroke, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
	TweenService:Create(Main.Shadow.Image, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 0.4}):Play()
	TweenService:Create(Topbar.CornerRepair, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Topbar.Divider, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Main, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 500, 0, 475)}):Play()
	TweenService:Create(Topbar, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 500, 0, 45)}):Play()
	TabList.Visible = true
	wait(0.2)

	Elements.Visible = true

	for _, tab in ipairs(Elements:GetChildren()) do
		if tab.Name ~= "Template" and tab.ClassName == "ScrollingFrame" and tab.Name ~= "Placeholder" then
			for _, element in ipairs(tab:GetChildren()) do
				if element.ClassName == "Frame" then
					if element.Name ~= "SectionSpacing" and element.Name ~= "Placeholder" then
						if element.Name == "SectionTitle" then
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
						else
							TweenService:Create(element, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
							TweenService:Create(element.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
						end
						for _, child in ipairs(element:GetChildren()) do
							if child.ClassName == "Frame" or child.ClassName == "TextLabel" or child.ClassName == "TextBox" or child.ClassName == "ImageButton" or child.ClassName == "ImageLabel" then
								child.Visible = true
							end
						end
					end
				end
			end
		end
	end


	wait(0.1)

	for _, tabbtn in ipairs(TabList:GetChildren()) do
		if tabbtn.ClassName == "Frame" and tabbtn.Name ~= "Placeholder" then
			if tostring(Elements.UIPageLayout.CurrentPage) == tabbtn.Title.Text then
				TweenService:Create(tabbtn, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
				TweenService:Create(tabbtn.Image, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0}):Play()
				TweenService:Create(tabbtn.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
				TweenService:Create(tabbtn.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
				TweenService:Create(tabbtn.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.9}):Play()
			else
				TweenService:Create(tabbtn, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.7}):Play()
				TweenService:Create(tabbtn.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.7}):Play()
				TweenService:Create(tabbtn.Image, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.2}):Play()
				TweenService:Create(tabbtn.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0.2}):Play()
				TweenService:Create(tabbtn.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			end

		end
	end


	wait(0.5)
	Debounce = false
end

function Minimise()
	Debounce = true
	Topbar.ChangeSize.Image = "rbxassetid://"..11036884234

	for _, tabbtn in ipairs(TabList:GetChildren()) do
		if tabbtn.ClassName == "Frame" and tabbtn.Name ~= "Placeholder" then
			TweenService:Create(tabbtn, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
			TweenService:Create(tabbtn.Image, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
			TweenService:Create(tabbtn.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
			TweenService:Create(tabbtn.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
			TweenService:Create(tabbtn.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
		end
	end

	for _, tab in ipairs(Elements:GetChildren()) do
		if tab.Name ~= "Template" and tab.ClassName == "ScrollingFrame" and tab.Name ~= "Placeholder" then
			for _, element in ipairs(tab:GetChildren()) do
				if element.ClassName == "Frame" then
					if element.Name ~= "SectionSpacing" and element.Name ~= "Placeholder" then
						if element.Name == "SectionTitle" then
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						else
							TweenService:Create(element, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
							TweenService:Create(element.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
							TweenService:Create(element.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						end
						for _, child in ipairs(element:GetChildren()) do
							if child.ClassName == "Frame" or child.ClassName == "TextLabel" or child.ClassName == "TextBox" or child.ClassName == "ImageButton" or child.ClassName == "ImageLabel" then
								child.Visible = false
							end
						end
					end
				end
			end
		end
	end

	TweenService:Create(Topbar.UIStroke, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
	TweenService:Create(Main.Shadow.Image, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
	TweenService:Create(Topbar.CornerRepair, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
	TweenService:Create(Topbar.Divider, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
	TweenService:Create(Main, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 495, 0, 45)}):Play()
	TweenService:Create(Topbar, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 495, 0, 45)}):Play()

	wait(0.3)

	Elements.Visible = false
	TabList.Visible = false

	wait(0.2)
	Debounce = false
end

function RayfieldLibrary:CreateWindow(Settings)
	local Passthrough = false
	Topbar.Title.Text = Settings.Name
	Main.Size = UDim2.new(0, 450, 0, 260)
	Main.Visible = true
	Main.BackgroundTransparency = 1
	LoadingFrame.Title.TextTransparency = 1
	LoadingFrame.Subtitle.TextTransparency = 1
	Main.Shadow.Image.ImageTransparency = 1
	LoadingFrame.Version.TextTransparency = 1
	LoadingFrame.Title.Text = Settings.LoadingTitle or "Rayfield Interface Suite"
	LoadingFrame.Subtitle.Text = Settings.LoadingSubtitle or "by Sirius"
	if Settings.LoadingTitle ~= "Rayfield Interface Suite" then
		LoadingFrame.Version.Text = "Rayfield UI"
	end
	Topbar.Visible = false
	Elements.Visible = false
	LoadingFrame.Visible = true


	pcall(function()
		if not Settings.ConfigurationSaving.FileName then
			Settings.ConfigurationSaving.FileName = tostring(game.PlaceId)
		end
		if not isfolder(RayfieldFolder.."/".."Configuration Folders") then

		end
		if Settings.ConfigurationSaving.Enabled == nil then
			Settings.ConfigurationSaving.Enabled = false
		end
		CFileName = Settings.ConfigurationSaving.FileName
		ConfigurationFolder = Settings.ConfigurationSaving.FolderName or ConfigurationFolder
		CEnabled = Settings.ConfigurationSaving.Enabled

		if Settings.ConfigurationSaving.Enabled then
			if not isfolder(ConfigurationFolder) then
				makefolder(ConfigurationFolder)
			end	
		end
	end)

	AddDraggingFunctionality(Topbar,Main)

	for _, TabButton in ipairs(TabList:GetChildren()) do
		if TabButton.ClassName == "Frame" and TabButton.Name ~= "Placeholder" then
			TabButton.BackgroundTransparency = 1
			TabButton.Title.TextTransparency = 1
			TabButton.Shadow.ImageTransparency = 1
			TabButton.Image.ImageTransparency = 1
			TabButton.UIStroke.Transparency = 1
		end
	end

	if Settings.Discord then
		if not isfolder(RayfieldFolder.."/Discord Invites") then
			makefolder(RayfieldFolder.."/Discord Invites")
		end
		if not isfile(RayfieldFolder.."/Discord Invites".."/"..Settings.Discord.Invite..ConfigurationExtension) then
			if request then
				request({
					Url = 'http://127.0.0.1:6463/rpc?v=1',
					Method = 'POST',
					Headers = {
						['Content-Type'] = 'application/json',
						Origin = 'https://discord.com'
					},
					Body = HttpService:JSONEncode({
						cmd = 'INVITE_BROWSER',
						nonce = HttpService:GenerateGUID(false),
						args = {code = Settings.Discord.Invite}
					})
				})
			end

			if Settings.Discord.RememberJoins then -- We do logic this way so if the developer changes this setting, the user still won't be prompted, only new users
				writefile(RayfieldFolder.."/Discord Invites".."/"..Settings.Discord.Invite..ConfigurationExtension,"Rayfield RememberJoins is true for this invite, this invite will not ask you to join again")
			end
		else

		end
	end

	if Settings.KeySystem then
		if not Settings.KeySettings then
			Passthrough = true
			return
		end

		if not isfolder(RayfieldFolder.."/Key System") then
			makefolder(RayfieldFolder.."/Key System")
		end

		if typeof(Settings.KeySettings.Key) == "string" then Settings.KeySettings.Key = {Settings.KeySettings.Key} end

		if Settings.KeySettings.GrabKeyFromSite then
			for i, Key in ipairs(Settings.KeySettings.Key) do
				local Success, Response = pcall(function()
					Settings.KeySettings.Key[i] = tostring(game:HttpGet(Key):gsub("[\n\r]", " "))
					Settings.KeySettings.Key[i] = string.gsub(Settings.KeySettings.Key[i], " ", "")
				end)
				if not Success then
					print("Rayfield | "..Key.." Error " ..tostring(Response))
				end
			end
		end

		if not Settings.KeySettings.FileName then
			Settings.KeySettings.FileName = "No file name specified"
		end

		if isfile(RayfieldFolder.."/Key System".."/"..Settings.KeySettings.FileName..ConfigurationExtension) then
			for _, MKey in ipairs(Settings.KeySettings.Key) do
				if string.find(readfile(RayfieldFolder.."/Key System".."/"..Settings.KeySettings.FileName..ConfigurationExtension), MKey) then
					Passthrough = true
				end
			end
		end

		if not Passthrough then
			local AttemptsRemaining = math.random(2,6)
			Rayfield.Enabled = false
			local KeyUI = game:GetObjects("rbxassetid://11380036235")[1]

			if gethui then
				KeyUI.Parent = gethui()
			elseif syn.protect_gui then
				syn.protect_gui(Rayfield)
				KeyUI.Parent = CoreGui
			else
				KeyUI.Parent = CoreGui
			end

			if gethui then
				for _, Interface in ipairs(gethui():GetChildren()) do
					if Interface.Name == KeyUI.Name and Interface ~= KeyUI then
						Interface.Enabled = false
						Interface.Name = "KeyUI-Old"
					end
				end
			else
				for _, Interface in ipairs(CoreGui:GetChildren()) do
					if Interface.Name == KeyUI.Name and Interface ~= KeyUI then
						Interface.Enabled = false
						Interface.Name = "KeyUI-Old"
					end
				end
			end

			local KeyMain = KeyUI.Main
			KeyMain.Title.Text = Settings.KeySettings.Title or Settings.Name
			KeyMain.Subtitle.Text = Settings.KeySettings.Subtitle or "Key System"
			KeyMain.NoteMessage.Text = Settings.KeySettings.Note or "No instructions"

			KeyMain.Size = UDim2.new(0, 467, 0, 175)
			KeyMain.BackgroundTransparency = 1
			KeyMain.Shadow.Image.ImageTransparency = 1
			KeyMain.Title.TextTransparency = 1
			KeyMain.Subtitle.TextTransparency = 1
			KeyMain.KeyNote.TextTransparency = 1
			KeyMain.Input.BackgroundTransparency = 1
			KeyMain.Input.UIStroke.Transparency = 1
			KeyMain.Input.InputBox.TextTransparency = 1
			KeyMain.NoteTitle.TextTransparency = 1
			KeyMain.NoteMessage.TextTransparency = 1
			KeyMain.Hide.ImageTransparency = 1

			TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 500, 0, 187)}):Play()
			TweenService:Create(KeyMain.Shadow.Image, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 0.5}):Play()
			wait(0.05)
			TweenService:Create(KeyMain.Title, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
			TweenService:Create(KeyMain.Subtitle, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
			wait(0.05)
			TweenService:Create(KeyMain.KeyNote, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
			TweenService:Create(KeyMain.Input, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(KeyMain.Input.UIStroke, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(KeyMain.Input.InputBox, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
			wait(0.05)
			TweenService:Create(KeyMain.NoteTitle, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
			TweenService:Create(KeyMain.NoteMessage, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
			wait(0.15)
			TweenService:Create(KeyMain.Hide, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {ImageTransparency = 0.3}):Play()


			KeyUI.Main.Input.InputBox.FocusLost:Connect(function()
				if #KeyUI.Main.Input.InputBox.Text == 0 then return end
				local KeyFound = false
				local FoundKey = ''
				for _, MKey in ipairs(Settings.KeySettings.Key) do
					if string.find(KeyMain.Input.InputBox.Text, MKey) then
						KeyFound = true
						FoundKey = MKey
					end
				end
				if KeyFound then 
					TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
					TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 467, 0, 175)}):Play()
					TweenService:Create(KeyMain.Shadow.Image, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
					TweenService:Create(KeyMain.Title, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(KeyMain.Subtitle, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(KeyMain.KeyNote, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(KeyMain.Input, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
					TweenService:Create(KeyMain.Input.UIStroke, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					TweenService:Create(KeyMain.Input.InputBox, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(KeyMain.NoteTitle, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(KeyMain.NoteMessage, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(KeyMain.Hide, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
					wait(0.51)
					Passthrough = true
					if Settings.KeySettings.SaveKey then
						if writefile then
							writefile(RayfieldFolder.."/Key System".."/"..Settings.KeySettings.FileName..ConfigurationExtension, FoundKey)
						end
						RayfieldLibrary:Notify({Title = "Key System", Content = "The key for this script has been saved successfully"})
					end
				else
					if AttemptsRemaining == 0 then
						TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
						TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 467, 0, 175)}):Play()
						TweenService:Create(KeyMain.Shadow.Image, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
						TweenService:Create(KeyMain.Title, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						TweenService:Create(KeyMain.Subtitle, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						TweenService:Create(KeyMain.KeyNote, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						TweenService:Create(KeyMain.Input, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
						TweenService:Create(KeyMain.Input.UIStroke, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
						TweenService:Create(KeyMain.Input.InputBox, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						TweenService:Create(KeyMain.NoteTitle, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						TweenService:Create(KeyMain.NoteMessage, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						TweenService:Create(KeyMain.Hide, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
						wait(0.45)
						game.Players.LocalPlayer:Kick("No Attempts Remaining")
						game:Shutdown()
					end
					KeyMain.Input.InputBox.Text = ""
					AttemptsRemaining = AttemptsRemaining - 1
					TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 467, 0, 175)}):Play()
					TweenService:Create(KeyMain, TweenInfo.new(0.4, Enum.EasingStyle.Elastic), {Position = UDim2.new(0.495,0,0.5,0)}):Play()
					wait(0.1)
					TweenService:Create(KeyMain, TweenInfo.new(0.4, Enum.EasingStyle.Elastic), {Position = UDim2.new(0.505,0,0.5,0)}):Play()
					wait(0.1)
					TweenService:Create(KeyMain, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {Position = UDim2.new(0.5,0,0.5,0)}):Play()
					TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 500, 0, 187)}):Play()
				end
			end)

			KeyMain.Hide.MouseButton1Click:Connect(function()
				TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
				TweenService:Create(KeyMain, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 467, 0, 175)}):Play()
				TweenService:Create(KeyMain.Shadow.Image, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
				TweenService:Create(KeyMain.Title, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
				TweenService:Create(KeyMain.Subtitle, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
				TweenService:Create(KeyMain.KeyNote, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
				TweenService:Create(KeyMain.Input, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
				TweenService:Create(KeyMain.Input.UIStroke, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
				TweenService:Create(KeyMain.Input.InputBox, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
				TweenService:Create(KeyMain.NoteTitle, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
				TweenService:Create(KeyMain.NoteMessage, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
				TweenService:Create(KeyMain.Hide, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
				wait(0.51)
				RayfieldLibrary:Destroy()
				KeyUI:Destroy()
			end)
		else
			Passthrough = true
		end
	end
	if Settings.KeySystem then
		repeat wait() until Passthrough
	end

	Notifications.Template.Visible = false
	Notifications.Visible = true
	Rayfield.Enabled = true
	wait(0.5)
	TweenService:Create(Main, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Main.Shadow.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.55}):Play()
	wait(0.1)
	TweenService:Create(LoadingFrame.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
	wait(0.05)
	TweenService:Create(LoadingFrame.Subtitle, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
	wait(0.05)
	TweenService:Create(LoadingFrame.Version, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()

	Elements.Template.LayoutOrder = 100000
	Elements.Template.Visible = false

	Elements.UIPageLayout.FillDirection = Enum.FillDirection.Horizontal
	TabList.Template.Visible = false

	-- Tab
	local FirstTab = false
	local Window = {}
	function Window:CreateTab(Name,Image)
		local SDone = false
		local TabButton = TabList.Template:Clone()
		TabButton.Name = Name
		TabButton.Title.Text = Name
		TabButton.Parent = TabList
		TabButton.Title.TextWrapped = false
		TabButton.Size = UDim2.new(0, TabButton.Title.TextBounds.X + 30, 0, 30)

		if Image then
			TabButton.Title.AnchorPoint = Vector2.new(0, 0.5)
			TabButton.Title.Position = UDim2.new(0, 37, 0.5, 0)
			TabButton.Image.Image = "rbxassetid://"..Image
			TabButton.Image.Visible = true
			TabButton.Title.TextXAlignment = Enum.TextXAlignment.Left
			TabButton.Size = UDim2.new(0, TabButton.Title.TextBounds.X + 46, 0, 30)
		end

		TabButton.BackgroundTransparency = 1
		TabButton.Title.TextTransparency = 1
		TabButton.Shadow.ImageTransparency = 1
		TabButton.Image.ImageTransparency = 1
		TabButton.UIStroke.Transparency = 1

		TabButton.Visible = true

		-- Create Elements Page
		local TabPage = Elements.Template:Clone()
		TabPage.Name = Name
		TabPage.Visible = true

		TabPage.LayoutOrder = #Elements:GetChildren()

		for _, TemplateElement in ipairs(TabPage:GetChildren()) do
			if TemplateElement.ClassName == "Frame" and TemplateElement.Name ~= "Placeholder" then
				TemplateElement:Destroy()
			end
		end

		TabPage.Parent = Elements
		if not FirstTab then
			Elements.UIPageLayout.Animated = false
			Elements.UIPageLayout:JumpTo(TabPage)
			Elements.UIPageLayout.Animated = true
		end

		if SelectedTheme ~= RayfieldLibrary.Theme.Default then
			TabButton.Shadow.Visible = false
		end
		TabButton.UIStroke.Color = SelectedTheme.TabStroke
		-- Animate
		wait(0.1)
		if FirstTab then
			TabButton.BackgroundColor3 = SelectedTheme.TabBackground
			TabButton.Image.ImageColor3 = SelectedTheme.TabTextColor
			TabButton.Title.TextColor3 = SelectedTheme.TabTextColor
			TweenService:Create(TabButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.7}):Play()
			TweenService:Create(TabButton.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0.2}):Play()
			TweenService:Create(TabButton.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.2}):Play()
			TweenService:Create(TabButton.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()

			TweenService:Create(TabButton.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.7}):Play()
		else
			FirstTab = Name
			TabButton.BackgroundColor3 = SelectedTheme.TabBackgroundSelected
			TabButton.Image.ImageColor3 = SelectedTheme.SelectedTabTextColor
			TabButton.Title.TextColor3 = SelectedTheme.SelectedTabTextColor
			TweenService:Create(TabButton.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.9}):Play()
			TweenService:Create(TabButton.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0}):Play()
			TweenService:Create(TabButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(TabButton.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
		end


		TabButton.Interact.MouseButton1Click:Connect(function()
			if Minimised then return end
			TweenService:Create(TabButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(TabButton.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
			TweenService:Create(TabButton.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
			TweenService:Create(TabButton.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0}):Play()
			TweenService:Create(TabButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.TabBackgroundSelected}):Play()
			TweenService:Create(TabButton.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextColor3 = SelectedTheme.SelectedTabTextColor}):Play()
			TweenService:Create(TabButton.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageColor3 = SelectedTheme.SelectedTabTextColor}):Play()
			TweenService:Create(TabButton.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.9}):Play()

			for _, OtherTabButton in ipairs(TabList:GetChildren()) do
				if OtherTabButton.Name ~= "Template" and OtherTabButton.ClassName == "Frame" and OtherTabButton ~= TabButton and OtherTabButton.Name ~= "Placeholder" then
					TweenService:Create(OtherTabButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.TabBackground}):Play()
					TweenService:Create(OtherTabButton.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextColor3 = SelectedTheme.TabTextColor}):Play()
					TweenService:Create(OtherTabButton.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageColor3 = SelectedTheme.TabTextColor}):Play()
					TweenService:Create(OtherTabButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0.7}):Play()
					TweenService:Create(OtherTabButton.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0.2}):Play()
					TweenService:Create(OtherTabButton.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.2}):Play()
					TweenService:Create(OtherTabButton.Shadow, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ImageTransparency = 0.7}):Play()
					TweenService:Create(OtherTabButton.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				end
			end
			if Elements.UIPageLayout.CurrentPage ~= TabPage then
				TweenService:Create(Elements, TweenInfo.new(1, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 460,0, 330)}):Play()
				Elements.UIPageLayout:JumpTo(TabPage)
				wait(0.2)
				TweenService:Create(Elements, TweenInfo.new(0.8, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 475,0, 366)}):Play()
			end

		end)

		local Tab = {}

		-- Button
		function Tab:CreateButton(ButtonSettings)
			local ButtonValue = {}

			local Button = Elements.Template.Button:Clone()
			Button.Name = ButtonSettings.Name
			Button.Title.Text = ButtonSettings.Name
			Button.Visible = true
			Button.Parent = TabPage

			Button.BackgroundTransparency = 1
			Button.UIStroke.Transparency = 1
			Button.Title.TextTransparency = 1

			TweenService:Create(Button, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Button.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Button.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	


			Button.Interact.MouseButton1Click:Connect(function()
				local Success, Response = pcall(ButtonSettings.Callback)
				if not Success then
					TweenService:Create(Button, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
					TweenService:Create(Button.ElementIndicator, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(Button.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					Button.Title.Text = "Callback Error"
					print("Rayfield | "..ButtonSettings.Name.." Callback Error " ..tostring(Response))
					wait(0.5)
					Button.Title.Text = ButtonSettings.Name
					TweenService:Create(Button, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Button.ElementIndicator, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0.9}):Play()
					TweenService:Create(Button.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				else
					SaveConfiguration()
					TweenService:Create(Button, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
					TweenService:Create(Button.ElementIndicator, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
					TweenService:Create(Button.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					wait(0.2)
					TweenService:Create(Button, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Button.ElementIndicator, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0.9}):Play()
					TweenService:Create(Button.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				end
			end)

			Button.MouseEnter:Connect(function()
				TweenService:Create(Button, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
				TweenService:Create(Button.ElementIndicator, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0.7}):Play()
			end)

			Button.MouseLeave:Connect(function()
				TweenService:Create(Button, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
				TweenService:Create(Button.ElementIndicator, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {TextTransparency = 0.9}):Play()
			end)

			function ButtonValue:Set(NewButton)
				Button.Title.Text = NewButton
				Button.Name = NewButton
			end

			return ButtonValue
		end

		-- ColorPicker
		function Tab:CreateColorPicker(ColorPickerSettings) -- by Throit
			ColorPickerSettings.Type = "ColorPicker"
			local ColorPicker = Elements.Template.ColorPicker:Clone()
			local Background = ColorPicker.CPBackground
			local Display = Background.Display
			local Main = Background.MainCP
			local Slider = ColorPicker.ColorSlider
			ColorPicker.ClipsDescendants = true
			ColorPicker.Name = ColorPickerSettings.Name
			ColorPicker.Title.Text = ColorPickerSettings.Name
			ColorPicker.Visible = true
			ColorPicker.Parent = TabPage
			ColorPicker.Size = UDim2.new(1, -10, 0.028, 35)
			Background.Size = UDim2.new(0, 39, 0, 22)
			Display.BackgroundTransparency = 0
			Main.MainPoint.ImageTransparency = 1
			ColorPicker.Interact.Size = UDim2.new(1, 0, 1, 0)
			ColorPicker.Interact.Position = UDim2.new(0.5, 0, 0.5, 0)
			ColorPicker.RGB.Position = UDim2.new(0, 17, 0, 70)
			ColorPicker.HexInput.Position = UDim2.new(0, 17, 0, 90)
			Main.ImageTransparency = 1
			Background.BackgroundTransparency = 1



			local opened = false 
			local mouse = game.Players.LocalPlayer:GetMouse()
			Main.Image = "http://www.roblox.com/asset/?id=11415645739"
			local mainDragging = false 
			local sliderDragging = false 
			ColorPicker.Interact.MouseButton1Down:Connect(function()
				if not opened then
					opened = true 
					TweenService:Create(ColorPicker, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(1, -10, 0.224, 40)}):Play()
					TweenService:Create(Background, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 173, 0, 86)}):Play()
					TweenService:Create(Display, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
					TweenService:Create(ColorPicker.Interact, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Position = UDim2.new(0.289, 0, 0.5, 0)}):Play()
					TweenService:Create(ColorPicker.RGB, TweenInfo.new(0.8, Enum.EasingStyle.Quint), {Position = UDim2.new(0, 17, 0, 40)}):Play()
					TweenService:Create(ColorPicker.HexInput, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Position = UDim2.new(0, 17, 0, 73)}):Play()
					TweenService:Create(ColorPicker.Interact, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0.574, 0, 1, 0)}):Play()
					TweenService:Create(Main.MainPoint, TweenInfo.new(0.2, Enum.EasingStyle.Quint), {ImageTransparency = 0}):Play()
					TweenService:Create(Main, TweenInfo.new(0.2, Enum.EasingStyle.Quint), {ImageTransparency = 0.1}):Play()
					TweenService:Create(Background, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
				else
					opened = false
					TweenService:Create(ColorPicker, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(1, -10, 0.028, 35)}):Play()
					TweenService:Create(Background, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 39, 0, 22)}):Play()
					TweenService:Create(ColorPicker.Interact, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Size = UDim2.new(1, 0, 1, 0)}):Play()
					TweenService:Create(ColorPicker.Interact, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Position = UDim2.new(0.5, 0, 0.5, 0)}):Play()
					TweenService:Create(ColorPicker.RGB, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Position = UDim2.new(0, 17, 0, 70)}):Play()
					TweenService:Create(ColorPicker.HexInput, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Position = UDim2.new(0, 17, 0, 90)}):Play()
					TweenService:Create(Display, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
					TweenService:Create(Main.MainPoint, TweenInfo.new(0.2, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
					TweenService:Create(Main, TweenInfo.new(0.2, Enum.EasingStyle.Quint), {ImageTransparency = 1}):Play()
					TweenService:Create(Background, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
				end
			end)

			game:GetService("UserInputService").InputEnded:Connect(function(input, gameProcessed) if input.UserInputType == Enum.UserInputType.MouseButton1 then 
					mainDragging = false
					sliderDragging = false
				end end)
			Main.MouseButton1Down:Connect(function()
				if opened then
					mainDragging = true 
				end
			end)
			Main.MainPoint.MouseButton1Down:Connect(function()
				if opened then
					mainDragging = true 
				end
			end)
			Slider.MouseButton1Down:Connect(function()
				sliderDragging = true 
			end)
			Slider.SliderPoint.MouseButton1Down:Connect(function()
				sliderDragging = true 
			end)
			local h,s,v = ColorPickerSettings.Color:ToHSV()
			local color = Color3.fromHSV(h,s,v) 
			local hex = string.format("#%02X%02X%02X",color.R*0xFF,color.G*0xFF,color.B*0xFF)
			ColorPicker.HexInput.InputBox.Text = hex
			local function setDisplay()
				--Main
				Main.MainPoint.Position = UDim2.new(s,-Main.MainPoint.AbsoluteSize.X/2,1-v,-Main.MainPoint.AbsoluteSize.Y/2)
				Main.MainPoint.ImageColor3 = Color3.fromHSV(h,s,v)
				Background.BackgroundColor3 = Color3.fromHSV(h,1,1)
				Display.BackgroundColor3 = Color3.fromHSV(h,s,v)
				--Slider 
				local x = h * Slider.AbsoluteSize.X
				Slider.SliderPoint.Position = UDim2.new(0,x-Slider.SliderPoint.AbsoluteSize.X/2,0.5,0)
				Slider.SliderPoint.ImageColor3 = Color3.fromHSV(h,1,1)
				local color = Color3.fromHSV(h,s,v) 
				local r,g,b = math.floor((color.R*255)+0.5),math.floor((color.G*255)+0.5),math.floor((color.B*255)+0.5)
				ColorPicker.RGB.RInput.InputBox.Text = tostring(r)
				ColorPicker.RGB.GInput.InputBox.Text = tostring(g)
				ColorPicker.RGB.BInput.InputBox.Text = tostring(b)
				hex = string.format("#%02X%02X%02X",color.R*0xFF,color.G*0xFF,color.B*0xFF)
				ColorPicker.HexInput.InputBox.Text = hex
			end
			setDisplay()
			ColorPicker.HexInput.InputBox.FocusLost:Connect(function()
				if not pcall(function()
						local r, g, b = string.match(ColorPicker.HexInput.InputBox.Text, "^#?(%w%w)(%w%w)(%w%w)$")
						local rgbColor = Color3.fromRGB(tonumber(r, 16),tonumber(g, 16), tonumber(b, 16))
						h,s,v = rgbColor:ToHSV()
						hex = ColorPicker.HexInput.InputBox.Text
						setDisplay()
						ColorPickerSettings.Color = rgbColor
					end) 
				then 
					ColorPicker.HexInput.InputBox.Text = hex 
				end
				pcall(function()ColorPickerSettings.Callback(Color3.fromHSV(h,s,v))end)
				local r,g,b = math.floor((h*255)+0.5),math.floor((s*255)+0.5),math.floor((v*255)+0.5)
				ColorPickerSettings.Color = Color3.fromRGB(r,g,b)
				SaveConfiguration()
			end)
			--RGB
			local function rgbBoxes(box,toChange)
				local value = tonumber(box.Text) 
				local color = Color3.fromHSV(h,s,v) 
				local oldR,oldG,oldB = math.floor((color.R*255)+0.5),math.floor((color.G*255)+0.5),math.floor((color.B*255)+0.5)
				local save 
				if toChange == "R" then save = oldR;oldR = value elseif toChange == "G" then save = oldG;oldG = value else save = oldB;oldB = value end
				if value then 
					value = math.clamp(value,0,255)
					h,s,v = Color3.fromRGB(oldR,oldG,oldB):ToHSV()

					setDisplay()
				else 
					box.Text = tostring(save)
				end
				local r,g,b = math.floor((h*255)+0.5),math.floor((s*255)+0.5),math.floor((v*255)+0.5)
				ColorPickerSettings.Color = Color3.fromRGB(r,g,b)
				SaveConfiguration()
			end
			ColorPicker.RGB.RInput.InputBox.FocusLost:connect(function()
				rgbBoxes(ColorPicker.RGB.RInput.InputBox,"R")
				pcall(function()ColorPickerSettings.Callback(Color3.fromHSV(h,s,v))end)
			end)
			ColorPicker.RGB.GInput.InputBox.FocusLost:connect(function()
				rgbBoxes(ColorPicker.RGB.GInput.InputBox,"G")
				pcall(function()ColorPickerSettings.Callback(Color3.fromHSV(h,s,v))end)
			end)
			ColorPicker.RGB.BInput.InputBox.FocusLost:connect(function()
				rgbBoxes(ColorPicker.RGB.BInput.InputBox,"B")
				pcall(function()ColorPickerSettings.Callback(Color3.fromHSV(h,s,v))end)
			end)

			game:GetService("RunService").RenderStepped:connect(function()
				if mainDragging then 
					local localX = math.clamp(mouse.X-Main.AbsolutePosition.X,0,Main.AbsoluteSize.X)
					local localY = math.clamp(mouse.Y-Main.AbsolutePosition.Y,0,Main.AbsoluteSize.Y)
					Main.MainPoint.Position = UDim2.new(0,localX-Main.MainPoint.AbsoluteSize.X/2,0,localY-Main.MainPoint.AbsoluteSize.Y/2)
					s = localX / Main.AbsoluteSize.X
					v = 1 - (localY / Main.AbsoluteSize.Y)
					Display.BackgroundColor3 = Color3.fromHSV(h,s,v)
					Main.MainPoint.ImageColor3 = Color3.fromHSV(h,s,v)
					Background.BackgroundColor3 = Color3.fromHSV(h,1,1)
					local color = Color3.fromHSV(h,s,v) 
					local r,g,b = math.floor((color.R*255)+0.5),math.floor((color.G*255)+0.5),math.floor((color.B*255)+0.5)
					ColorPicker.RGB.RInput.InputBox.Text = tostring(r)
					ColorPicker.RGB.GInput.InputBox.Text = tostring(g)
					ColorPicker.RGB.BInput.InputBox.Text = tostring(b)
					ColorPicker.HexInput.InputBox.Text = string.format("#%02X%02X%02X",color.R*0xFF,color.G*0xFF,color.B*0xFF)
					pcall(function()ColorPickerSettings.Callback(Color3.fromHSV(h,s,v))end)
					ColorPickerSettings.Color = Color3.fromRGB(r,g,b)
					SaveConfiguration()
				end
				if sliderDragging then 
					local localX = math.clamp(mouse.X-Slider.AbsolutePosition.X,0,Slider.AbsoluteSize.X)
					h = localX / Slider.AbsoluteSize.X
					Display.BackgroundColor3 = Color3.fromHSV(h,s,v)
					Slider.SliderPoint.Position = UDim2.new(0,localX-Slider.SliderPoint.AbsoluteSize.X/2,0.5,0)
					Slider.SliderPoint.ImageColor3 = Color3.fromHSV(h,1,1)
					Background.BackgroundColor3 = Color3.fromHSV(h,1,1)
					Main.MainPoint.ImageColor3 = Color3.fromHSV(h,s,v)
					local color = Color3.fromHSV(h,s,v) 
					local r,g,b = math.floor((color.R*255)+0.5),math.floor((color.G*255)+0.5),math.floor((color.B*255)+0.5)
					ColorPicker.RGB.RInput.InputBox.Text = tostring(r)
					ColorPicker.RGB.GInput.InputBox.Text = tostring(g)
					ColorPicker.RGB.BInput.InputBox.Text = tostring(b)
					ColorPicker.HexInput.InputBox.Text = string.format("#%02X%02X%02X",color.R*0xFF,color.G*0xFF,color.B*0xFF)
					pcall(function()ColorPickerSettings.Callback(Color3.fromHSV(h,s,v))end)
					ColorPickerSettings.Color = Color3.fromRGB(r,g,b)
					SaveConfiguration()
				end
			end)

			if Settings.ConfigurationSaving then
				if Settings.ConfigurationSaving.Enabled and ColorPickerSettings.Flag then
					RayfieldLibrary.Flags[ColorPickerSettings.Flag] = ColorPickerSettings
				end
			end

			function ColorPickerSettings:Set(RGBColor)
				ColorPickerSettings.Color = RGBColor
				h,s,v = ColorPickerSettings.Color:ToHSV()
				color = Color3.fromHSV(h,s,v)
				setDisplay()
			end

			return ColorPickerSettings
		end

		-- Section
		function Tab:CreateSection(SectionName)

			local SectionValue = {}

			if SDone then
				local SectionSpace = Elements.Template.SectionSpacing:Clone()
				SectionSpace.Visible = true
				SectionSpace.Parent = TabPage
			end

			local Section = Elements.Template.SectionTitle:Clone()
			Section.Title.Text = SectionName
			Section.Visible = true
			Section.Parent = TabPage

			Section.Title.TextTransparency = 1
			TweenService:Create(Section.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()

			function SectionValue:Set(NewSection)
				Section.Title.Text = NewSection
			end

			SDone = true

			return SectionValue
		end

		-- Label
		function Tab:CreateLabel(LabelText)
			local LabelValue = {}

			local Label = Elements.Template.Label:Clone()
			Label.Title.Text = LabelText
			Label.Visible = true
			Label.Parent = TabPage

			Label.BackgroundTransparency = 1
			Label.UIStroke.Transparency = 1
			Label.Title.TextTransparency = 1

			Label.BackgroundColor3 = SelectedTheme.SecondaryElementBackground
			Label.UIStroke.Color = SelectedTheme.SecondaryElementStroke

			TweenService:Create(Label, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Label.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Label.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	

			function LabelValue:Set(NewLabel)
				Label.Title.Text = NewLabel
			end

			return LabelValue
		end

		-- Paragraph
		function Tab:CreateParagraph(ParagraphSettings)
			local ParagraphValue = {}

			local Paragraph = Elements.Template.Paragraph:Clone()
			Paragraph.Title.Text = ParagraphSettings.Title
			Paragraph.Content.Text = ParagraphSettings.Content
			Paragraph.Visible = true
			Paragraph.Parent = TabPage

			Paragraph.Content.Size = UDim2.new(0, 438, 0, Paragraph.Content.TextBounds.Y)
			Paragraph.Content.Position = UDim2.new(1, -10, 0.575,0 )
			Paragraph.Size = UDim2.new(1, -10, 0, Paragraph.Content.TextBounds.Y + 40)

			Paragraph.BackgroundTransparency = 1
			Paragraph.UIStroke.Transparency = 1
			Paragraph.Title.TextTransparency = 1
			Paragraph.Content.TextTransparency = 1

			Paragraph.BackgroundColor3 = SelectedTheme.SecondaryElementBackground
			Paragraph.UIStroke.Color = SelectedTheme.SecondaryElementStroke

			TweenService:Create(Paragraph, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Paragraph.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Paragraph.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	
			TweenService:Create(Paragraph.Content, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	

			function ParagraphValue:Set(NewParagraphSettings)
				Paragraph.Title.Text = NewParagraphSettings.Title
				Paragraph.Content.Text = NewParagraphSettings.Content
			end

			return ParagraphValue
		end

		-- Input
		function Tab:CreateInput(InputSettings)
			local Input = Elements.Template.Input:Clone()
			Input.Name = InputSettings.Name
			Input.Title.Text = InputSettings.Name
			Input.Visible = true
			Input.Parent = TabPage

			Input.BackgroundTransparency = 1
			Input.UIStroke.Transparency = 1
			Input.Title.TextTransparency = 1

			Input.InputFrame.BackgroundColor3 = SelectedTheme.InputBackground
			Input.InputFrame.UIStroke.Color = SelectedTheme.InputStroke

			TweenService:Create(Input, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Input.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Input.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	

			Input.InputFrame.InputBox.PlaceholderText = InputSettings.PlaceholderText
			Input.InputFrame.Size = UDim2.new(0, Input.InputFrame.InputBox.TextBounds.X + 24, 0, 30)

			Input.InputFrame.InputBox.FocusLost:Connect(function()


				local Success, Response = pcall(function()
					InputSettings.Callback(Input.InputFrame.InputBox.Text)
				end)
				if not Success then
					TweenService:Create(Input, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
					TweenService:Create(Input.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					Input.Title.Text = "Callback Error"
					print("Rayfield | "..InputSettings.Name.." Callback Error " ..tostring(Response))
					wait(0.5)
					Input.Title.Text = InputSettings.Name
					TweenService:Create(Input, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Input.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				end

				if InputSettings.RemoveTextAfterFocusLost then
					Input.InputFrame.InputBox.Text = ""
				end
				SaveConfiguration()
			end)

			Input.MouseEnter:Connect(function()
				TweenService:Create(Input, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
			end)

			Input.MouseLeave:Connect(function()
				TweenService:Create(Input, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
			end)

			Input.InputFrame.InputBox:GetPropertyChangedSignal("Text"):Connect(function()
				TweenService:Create(Input.InputFrame, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Size = UDim2.new(0, Input.InputFrame.InputBox.TextBounds.X + 24, 0, 30)}):Play()
			end)

			local InputSettings = {}
			function InputSettings:Set(text) --Doesnt fire the event
				Input.InputFrame.InputBox.Text = text
			end
			return InputSettings
		end

		-- Dropdown
		function Tab:CreateDropdown(DropdownSettings)
			local Dropdown = Elements.Template.Dropdown:Clone()
			if string.find(DropdownSettings.Name,"closed") then
				Dropdown.Name = "Dropdown"
			else
				Dropdown.Name = DropdownSettings.Name
			end
			Dropdown.Title.Text = DropdownSettings.Name
			Dropdown.Visible = true
			Dropdown.Parent = TabPage

			Dropdown.List.Visible = false

			if typeof(DropdownSettings.CurrentOption) == "string" then
				DropdownSettings.CurrentOption = {DropdownSettings.CurrentOption}
			end

			if not DropdownSettings.MultipleOptions then
				DropdownSettings.CurrentOption = {DropdownSettings.CurrentOption[1]}
			end

			if DropdownSettings.MultipleOptions then
				if #DropdownSettings.CurrentOption == 1 then
					Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
				elseif #DropdownSettings.CurrentOption == 0 then
					Dropdown.Selected.Text = "None"
				else
					Dropdown.Selected.Text = "Various"
				end
			else
				Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
			end


			Dropdown.BackgroundTransparency = 1
			Dropdown.UIStroke.Transparency = 1
			Dropdown.Title.TextTransparency = 1

			Dropdown.Size = UDim2.new(1, -10, 0, 45)

			TweenService:Create(Dropdown, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Dropdown.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Dropdown.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	

			for _, ununusedoption in ipairs(Dropdown.List:GetChildren()) do
				if ununusedoption.ClassName == "Frame" and ununusedoption.Name ~= "Placeholder" then
					ununusedoption:Destroy()
				end
			end

			Dropdown.Toggle.Rotation = 180

			Dropdown.Interact.MouseButton1Click:Connect(function()
				TweenService:Create(Dropdown, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
				TweenService:Create(Dropdown.UIStroke, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
				wait(0.1)
				TweenService:Create(Dropdown, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
				TweenService:Create(Dropdown.UIStroke, TweenInfo.new(0.4, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				if Debounce then return end
				if Dropdown.List.Visible then
					Debounce = true
					TweenService:Create(Dropdown, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(1, -10, 0, 45)}):Play()
					for _, DropdownOpt in ipairs(Dropdown.List:GetChildren()) do
						if DropdownOpt.ClassName == "Frame" and DropdownOpt.Name ~= "Placeholder" then
							TweenService:Create(DropdownOpt, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
							TweenService:Create(DropdownOpt.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
							TweenService:Create(DropdownOpt.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
						end
					end
					TweenService:Create(Dropdown.List, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ScrollBarImageTransparency = 1}):Play()
					TweenService:Create(Dropdown.Toggle, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Rotation = 180}):Play()	
					wait(0.35)
					Dropdown.List.Visible = false
					Debounce = false
				else
					TweenService:Create(Dropdown, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(1, -10, 0, 180)}):Play()
					Dropdown.List.Visible = true
					TweenService:Create(Dropdown.List, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ScrollBarImageTransparency = 0.7}):Play()
					TweenService:Create(Dropdown.Toggle, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Rotation = 0}):Play()	
					for _, DropdownOpt in ipairs(Dropdown.List:GetChildren()) do
						if DropdownOpt.ClassName == "Frame" and DropdownOpt.Name ~= "Placeholder" then
							TweenService:Create(DropdownOpt, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
							TweenService:Create(DropdownOpt.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
							TweenService:Create(DropdownOpt.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
						end
					end
				end
			end)

			Dropdown.MouseEnter:Connect(function()
				if not Dropdown.List.Visible then
					TweenService:Create(Dropdown, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
				end
			end)

			Dropdown.MouseLeave:Connect(function()
				TweenService:Create(Dropdown, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
			end)

			for _, Option in ipairs(DropdownSettings.Options) do
				local DropdownOption = Elements.Template.Dropdown.List.Template:Clone()
				DropdownOption.Name = Option
				DropdownOption.Title.Text = Option
				DropdownOption.Parent = Dropdown.List
				DropdownOption.Visible = true

				if DropdownSettings.CurrentOption == Option then
					DropdownOption.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
				end

				DropdownOption.BackgroundTransparency = 1
				DropdownOption.UIStroke.Transparency = 1
				DropdownOption.Title.TextTransparency = 1

				--local Dropdown = Tab:CreateDropdown({
				--	Name = "Dropdown Example",
				--	Options = {"Option 1","Option 2"},
				--	CurrentOption = {"Option 1"},
				--  MultipleOptions = true,
				--	Flag = "Dropdown1",
				--	Callback = function(TableOfOptions)

				--	end,
				--})


				DropdownOption.Interact.ZIndex = 50
				DropdownOption.Interact.MouseButton1Click:Connect(function()
					if not DropdownSettings.MultipleOptions and table.find(DropdownSettings.CurrentOption, Option) then 
						return
					end

					if table.find(DropdownSettings.CurrentOption, Option) then
						table.remove(DropdownSettings.CurrentOption, table.find(DropdownSettings.CurrentOption, Option))
						if DropdownSettings.MultipleOptions then
							if #DropdownSettings.CurrentOption == 1 then
								Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
							elseif #DropdownSettings.CurrentOption == 0 then
								Dropdown.Selected.Text = "None"
							else
								Dropdown.Selected.Text = "Various"
							end
						else
							Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
						end
					else
						if not DropdownSettings.MultipleOptions then
							table.clear(DropdownSettings.CurrentOption)
						end
						table.insert(DropdownSettings.CurrentOption, Option)
						if DropdownSettings.MultipleOptions then
							if #DropdownSettings.CurrentOption == 1 then
								Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
							elseif #DropdownSettings.CurrentOption == 0 then
								Dropdown.Selected.Text = "None"
							else
								Dropdown.Selected.Text = "Various"
							end
						else
							Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
						end
						TweenService:Create(DropdownOption.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
						TweenService:Create(DropdownOption, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(40, 40, 40)}):Play()
						Debounce = true
						wait(0.2)
						TweenService:Create(DropdownOption.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
					end


					local Success, Response = pcall(function()
						DropdownSettings.Callback(DropdownSettings.CurrentOption)
					end)

					if not Success then
						TweenService:Create(Dropdown, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
						TweenService:Create(Dropdown.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
						Dropdown.Title.Text = "Callback Error"
						print("Rayfield | "..DropdownSettings.Name.." Callback Error " ..tostring(Response))
						wait(0.5)
						Dropdown.Title.Text = DropdownSettings.Name
						TweenService:Create(Dropdown, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
						TweenService:Create(Dropdown.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
					end

					for _, droption in ipairs(Dropdown.List:GetChildren()) do
						if droption.ClassName == "Frame" and droption.Name ~= "Placeholder" and not table.find(DropdownSettings.CurrentOption, droption.Name) then
							TweenService:Create(droption, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(30, 30, 30)}):Play()
						end
					end
					if not DropdownSettings.MultipleOptions then
						wait(0.1)
						TweenService:Create(Dropdown, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {Size = UDim2.new(1, -10, 0, 45)}):Play()
						for _, DropdownOpt in ipairs(Dropdown.List:GetChildren()) do
							if DropdownOpt.ClassName == "Frame" and DropdownOpt.Name ~= "Placeholder" then
								TweenService:Create(DropdownOpt, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {BackgroundTransparency = 1}):Play()
								TweenService:Create(DropdownOpt.UIStroke, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
								TweenService:Create(DropdownOpt.Title, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
							end
						end
						TweenService:Create(Dropdown.List, TweenInfo.new(0.3, Enum.EasingStyle.Quint), {ScrollBarImageTransparency = 1}):Play()
						TweenService:Create(Dropdown.Toggle, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Rotation = 180}):Play()	
						wait(0.35)
						Dropdown.List.Visible = false
					end
					Debounce = false	
					SaveConfiguration()
				end)
			end

			for _, droption in ipairs(Dropdown.List:GetChildren()) do
				if droption.ClassName == "Frame" and droption.Name ~= "Placeholder" then
					if not table.find(DropdownSettings.CurrentOption, droption.Name) then
						droption.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
					else
						droption.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
					end
				end
			end

			function DropdownSettings:Set(NewOption)
				DropdownSettings.CurrentOption = NewOption

				if typeof(DropdownSettings.CurrentOption) == "string" then
					DropdownSettings.CurrentOption = {DropdownSettings.CurrentOption}
				end

				if not DropdownSettings.MultipleOptions then
					DropdownSettings.CurrentOption = {DropdownSettings.CurrentOption[1]}
				end

				if DropdownSettings.MultipleOptions then
					if #DropdownSettings.CurrentOption == 1 then
						Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
					elseif #DropdownSettings.CurrentOption == 0 then
						Dropdown.Selected.Text = "None"
					else
						Dropdown.Selected.Text = "Various"
					end
				else
					Dropdown.Selected.Text = DropdownSettings.CurrentOption[1]
				end


				local Success, Response = pcall(function()
					DropdownSettings.Callback(NewOption)
				end)
				if not Success then
					TweenService:Create(Dropdown, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
					TweenService:Create(Dropdown.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					Dropdown.Title.Text = "Callback Error"
					print("Rayfield | "..DropdownSettings.Name.." Callback Error " ..tostring(Response))
					wait(0.5)
					Dropdown.Title.Text = DropdownSettings.Name
					TweenService:Create(Dropdown, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Dropdown.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				end

				for _, droption in ipairs(Dropdown.List:GetChildren()) do
					if droption.ClassName == "Frame" and droption.Name ~= "Placeholder" then
						if not table.find(DropdownSettings.CurrentOption, droption.Name) then
							droption.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
						else
							droption.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
						end
					end
				end
				--SaveConfiguration()
			end

			if Settings.ConfigurationSaving then
				if Settings.ConfigurationSaving.Enabled and DropdownSettings.Flag then
					RayfieldLibrary.Flags[DropdownSettings.Flag] = DropdownSettings
				end
			end

			return DropdownSettings
		end

		-- Keybind
		function Tab:CreateKeybind(KeybindSettings)
			local CheckingForKey = false
			local Keybind = Elements.Template.Keybind:Clone()
			Keybind.Name = KeybindSettings.Name
			Keybind.Title.Text = KeybindSettings.Name
			Keybind.Visible = true
			Keybind.Parent = TabPage

			Keybind.BackgroundTransparency = 1
			Keybind.UIStroke.Transparency = 1
			Keybind.Title.TextTransparency = 1

			Keybind.KeybindFrame.BackgroundColor3 = SelectedTheme.InputBackground
			Keybind.KeybindFrame.UIStroke.Color = SelectedTheme.InputStroke

			TweenService:Create(Keybind, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Keybind.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Keybind.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	

			Keybind.KeybindFrame.KeybindBox.Text = KeybindSettings.CurrentKeybind
			Keybind.KeybindFrame.Size = UDim2.new(0, Keybind.KeybindFrame.KeybindBox.TextBounds.X + 24, 0, 30)

			Keybind.KeybindFrame.KeybindBox.Focused:Connect(function()
				CheckingForKey = true
				Keybind.KeybindFrame.KeybindBox.Text = ""
			end)
			Keybind.KeybindFrame.KeybindBox.FocusLost:Connect(function()
				CheckingForKey = false
				if Keybind.KeybindFrame.KeybindBox.Text == nil or "" then
					Keybind.KeybindFrame.KeybindBox.Text = KeybindSettings.CurrentKeybind
					SaveConfiguration()
				end
			end)

			Keybind.MouseEnter:Connect(function()
				TweenService:Create(Keybind, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
			end)

			Keybind.MouseLeave:Connect(function()
				TweenService:Create(Keybind, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
			end)

			UserInputService.InputBegan:Connect(function(input, processed)

				if CheckingForKey then
					if input.KeyCode ~= Enum.KeyCode.Unknown and input.KeyCode ~= Enum.KeyCode.K then
						local SplitMessage = string.split(tostring(input.KeyCode), ".")
						local NewKeyNoEnum = SplitMessage[3]
						Keybind.KeybindFrame.KeybindBox.Text = tostring(NewKeyNoEnum)
						KeybindSettings.CurrentKeybind = tostring(NewKeyNoEnum)
						Keybind.KeybindFrame.KeybindBox:ReleaseFocus()
						SaveConfiguration()
					end
				elseif KeybindSettings.CurrentKeybind ~= nil and (input.KeyCode == Enum.KeyCode[KeybindSettings.CurrentKeybind] and not processed) then -- Test
					local Held = true
					local Connection
					Connection = input.Changed:Connect(function(prop)
						if prop == "UserInputState" then
							Connection:Disconnect()
							Held = false
						end
					end)

					if not KeybindSettings.HoldToInteract then
						local Success, Response = pcall(KeybindSettings.Callback)
						if not Success then
							TweenService:Create(Keybind, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
							TweenService:Create(Keybind.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
							Keybind.Title.Text = "Callback Error"
							print("Rayfield | "..KeybindSettings.Name.." Callback Error " ..tostring(Response))
							wait(0.5)
							Keybind.Title.Text = KeybindSettings.Name
							TweenService:Create(Keybind, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
							TweenService:Create(Keybind.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
						end
					else
						wait(0.25)
						if Held then
							local Loop; Loop = RunService.Stepped:Connect(function()
								if not Held then
									KeybindSettings.Callback(false) -- maybe pcall this
									Loop:Disconnect()
								else
									KeybindSettings.Callback(true) -- maybe pcall this
								end
							end)	
						end
					end
				end
			end)

			Keybind.KeybindFrame.KeybindBox:GetPropertyChangedSignal("Text"):Connect(function()
				TweenService:Create(Keybind.KeybindFrame, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Size = UDim2.new(0, Keybind.KeybindFrame.KeybindBox.TextBounds.X + 24, 0, 30)}):Play()
			end)

			function KeybindSettings:Set(NewKeybind)
				Keybind.KeybindFrame.KeybindBox.Text = tostring(NewKeybind)
				KeybindSettings.CurrentKeybind = tostring(NewKeybind)
				Keybind.KeybindFrame.KeybindBox:ReleaseFocus()
				SaveConfiguration()
			end
			if Settings.ConfigurationSaving then
				if Settings.ConfigurationSaving.Enabled and KeybindSettings.Flag then
					RayfieldLibrary.Flags[KeybindSettings.Flag] = KeybindSettings
				end
			end
			return KeybindSettings
		end

		-- Toggle
		function Tab:CreateToggle(ToggleSettings)
			local ToggleValue = {}

			local Toggle = Elements.Template.Toggle:Clone()
			Toggle.Name = ToggleSettings.Name
			Toggle.Title.Text = ToggleSettings.Name
			Toggle.Visible = true
			Toggle.Parent = TabPage

			Toggle.BackgroundTransparency = 1
			Toggle.UIStroke.Transparency = 1
			Toggle.Title.TextTransparency = 1
			Toggle.Switch.BackgroundColor3 = SelectedTheme.ToggleBackground

			if SelectedTheme ~= RayfieldLibrary.Theme.Default then
				Toggle.Switch.Shadow.Visible = false
			end

			TweenService:Create(Toggle, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Toggle.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	

			if not ToggleSettings.CurrentValue then
				Toggle.Switch.Indicator.Position = UDim2.new(1, -40, 0.5, 0)
				Toggle.Switch.Indicator.UIStroke.Color = SelectedTheme.ToggleDisabledStroke
				Toggle.Switch.Indicator.BackgroundColor3 = SelectedTheme.ToggleDisabled
				Toggle.Switch.UIStroke.Color = SelectedTheme.ToggleDisabledOuterStroke
			else
				Toggle.Switch.Indicator.Position = UDim2.new(1, -20, 0.5, 0)
				Toggle.Switch.Indicator.UIStroke.Color = SelectedTheme.ToggleEnabledStroke
				Toggle.Switch.Indicator.BackgroundColor3 = SelectedTheme.ToggleEnabled
				Toggle.Switch.UIStroke.Color = SelectedTheme.ToggleEnabledOuterStroke
			end

			Toggle.MouseEnter:Connect(function()
				TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
			end)

			Toggle.MouseLeave:Connect(function()
				TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
			end)

			Toggle.Interact.MouseButton1Click:Connect(function()
				if ToggleSettings.CurrentValue then
					ToggleSettings.CurrentValue = false
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.45, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Position = UDim2.new(1, -40, 0.5, 0)}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.4, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,12,0,12)}):Play()
					TweenService:Create(Toggle.Switch.Indicator.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = SelectedTheme.ToggleDisabledStroke}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.8, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {BackgroundColor3 = SelectedTheme.ToggleDisabled}):Play()
					TweenService:Create(Toggle.Switch.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = SelectedTheme.ToggleDisabledOuterStroke}):Play()
					wait(0.05)
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.4, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,17,0,17)}):Play()
					wait(0.15)
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()	
				else
					ToggleSettings.CurrentValue = true
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.5, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Position = UDim2.new(1, -20, 0.5, 0)}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.4, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,12,0,12)}):Play()
					TweenService:Create(Toggle.Switch.Indicator.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = SelectedTheme.ToggleEnabledStroke}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.8, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {BackgroundColor3 = SelectedTheme.ToggleEnabled}):Play()
					TweenService:Create(Toggle.Switch.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = SelectedTheme.ToggleEnabledOuterStroke}):Play()
					wait(0.05)
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.45, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,17,0,17)}):Play()	
					wait(0.15)
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()		
				end

				local Success, Response = pcall(function()
					ToggleSettings.Callback(ToggleSettings.CurrentValue)
				end)
				if not Success then
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					Toggle.Title.Text = "Callback Error"
					print("Rayfield | "..ToggleSettings.Name.." Callback Error " ..tostring(Response))
					wait(0.5)
					Toggle.Title.Text = ToggleSettings.Name
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				end


				SaveConfiguration()
			end)

			function ToggleSettings:Set(NewToggleValue)
				if NewToggleValue then
					ToggleSettings.CurrentValue = true
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.5, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Position = UDim2.new(1, -20, 0.5, 0)}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.4, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,12,0,12)}):Play()
					TweenService:Create(Toggle.Switch.Indicator.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = SelectedTheme.ToggleEnabledStroke}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.8, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {BackgroundColor3 = SelectedTheme.ToggleEnabled}):Play()
					TweenService:Create(Toggle.Switch.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = Color3.fromRGB(100,100,100)}):Play()
					wait(0.05)
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.45, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,17,0,17)}):Play()	
					wait(0.15)
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()	
				else
					ToggleSettings.CurrentValue = false
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.45, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Position = UDim2.new(1, -40, 0.5, 0)}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.4, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,12,0,12)}):Play()
					TweenService:Create(Toggle.Switch.Indicator.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = SelectedTheme.ToggleDisabledStroke}):Play()
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.8, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {BackgroundColor3 = SelectedTheme.ToggleDisabled}):Play()
					TweenService:Create(Toggle.Switch.UIStroke, TweenInfo.new(0.55, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Color = Color3.fromRGB(65,65,65)}):Play()
					wait(0.05)
					TweenService:Create(Toggle.Switch.Indicator, TweenInfo.new(0.4, Enum.EasingStyle.Quart, Enum.EasingDirection.Out), {Size = UDim2.new(0,17,0,17)}):Play()
					wait(0.15)
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()	
				end
				local Success, Response = pcall(function()
					ToggleSettings.Callback(ToggleSettings.CurrentValue)
				end)
				if not Success then
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					Toggle.Title.Text = "Callback Error"
					print("Rayfield | "..ToggleSettings.Name.." Callback Error " ..tostring(Response))
					wait(0.5)
					Toggle.Title.Text = ToggleSettings.Name
					TweenService:Create(Toggle, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Toggle.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				end
				SaveConfiguration()
			end

			if Settings.ConfigurationSaving then
				if Settings.ConfigurationSaving.Enabled and ToggleSettings.Flag then
					RayfieldLibrary.Flags[ToggleSettings.Flag] = ToggleSettings
				end
			end

			return ToggleSettings
		end

		-- Slider
		function Tab:CreateSlider(SliderSettings)
			local Dragging = false
			local Slider = Elements.Template.Slider:Clone()
			Slider.Name = SliderSettings.Name
			Slider.Title.Text = SliderSettings.Name
			Slider.Visible = true
			Slider.Parent = TabPage

			Slider.BackgroundTransparency = 1
			Slider.UIStroke.Transparency = 1
			Slider.Title.TextTransparency = 1

			if SelectedTheme ~= RayfieldLibrary.Theme.Default then
				Slider.Main.Shadow.Visible = false
			end

			Slider.Main.BackgroundColor3 = SelectedTheme.SliderBackground
			Slider.Main.UIStroke.Color = SelectedTheme.SliderStroke
			Slider.Main.Progress.BackgroundColor3 = SelectedTheme.SliderProgress

			TweenService:Create(Slider, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
			TweenService:Create(Slider.UIStroke, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
			TweenService:Create(Slider.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()	

			Slider.Main.Progress.Size =	UDim2.new(0, Slider.Main.AbsoluteSize.X * ((SliderSettings.CurrentValue + SliderSettings.Range[1]) / (SliderSettings.Range[2] - SliderSettings.Range[1])) > 5 and Slider.Main.AbsoluteSize.X * (SliderSettings.CurrentValue / (SliderSettings.Range[2] - SliderSettings.Range[1])) or 5, 1, 0)

			if not SliderSettings.Suffix then
				Slider.Main.Information.Text = tostring(SliderSettings.CurrentValue)
			else
				Slider.Main.Information.Text = tostring(SliderSettings.CurrentValue) .. " " .. SliderSettings.Suffix
			end


			Slider.MouseEnter:Connect(function()
				TweenService:Create(Slider, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackgroundHover}):Play()
			end)

			Slider.MouseLeave:Connect(function()
				TweenService:Create(Slider, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
			end)

			Slider.Main.Interact.InputBegan:Connect(function(Input)
				if Input.UserInputType == Enum.UserInputType.MouseButton1 then 
					Dragging = true 
				end 
			end)
			Slider.Main.Interact.InputEnded:Connect(function(Input) 
				if Input.UserInputType == Enum.UserInputType.MouseButton1 then 
					Dragging = false 
				end 
			end)

			Slider.Main.Interact.MouseButton1Down:Connect(function(X)
				local Current = Slider.Main.Progress.AbsolutePosition.X + Slider.Main.Progress.AbsoluteSize.X
				local Start = Current
				local Location = X
				local Loop; Loop = RunService.Stepped:Connect(function()
					if Dragging then
						Location = UserInputService:GetMouseLocation().X
						Current = Current + 0.025 * (Location - Start)

						if Location < Slider.Main.AbsolutePosition.X then
							Location = Slider.Main.AbsolutePosition.X
						elseif Location > Slider.Main.AbsolutePosition.X + Slider.Main.AbsoluteSize.X then
							Location = Slider.Main.AbsolutePosition.X + Slider.Main.AbsoluteSize.X
						end

						if Current < Slider.Main.AbsolutePosition.X + 5 then
							Current = Slider.Main.AbsolutePosition.X + 5
						elseif Current > Slider.Main.AbsolutePosition.X + Slider.Main.AbsoluteSize.X then
							Current = Slider.Main.AbsolutePosition.X + Slider.Main.AbsoluteSize.X
						end

						if Current <= Location and (Location - Start) < 0 then
							Start = Location
						elseif Current >= Location and (Location - Start) > 0 then
							Start = Location
						end
						TweenService:Create(Slider.Main.Progress, TweenInfo.new(0.45, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Size = UDim2.new(0, Current - Slider.Main.AbsolutePosition.X, 1, 0)}):Play()
						local NewValue = SliderSettings.Range[1] + (Location - Slider.Main.AbsolutePosition.X) / Slider.Main.AbsoluteSize.X * (SliderSettings.Range[2] - SliderSettings.Range[1])

						NewValue = math.floor(NewValue / SliderSettings.Increment + 0.5) * (SliderSettings.Increment * 10000000) / 10000000
						if not SliderSettings.Suffix then
							Slider.Main.Information.Text = tostring(NewValue)
						else
							Slider.Main.Information.Text = tostring(NewValue) .. " " .. SliderSettings.Suffix
						end

						if SliderSettings.CurrentValue ~= NewValue then
							local Success, Response = pcall(function()
								SliderSettings.Callback(NewValue)
							end)
							if not Success then
								TweenService:Create(Slider, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
								TweenService:Create(Slider.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
								Slider.Title.Text = "Callback Error"
								print("Rayfield | "..SliderSettings.Name.." Callback Error " ..tostring(Response))
								wait(0.5)
								Slider.Title.Text = SliderSettings.Name
								TweenService:Create(Slider, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
								TweenService:Create(Slider.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
							end

							SliderSettings.CurrentValue = NewValue
							SaveConfiguration()
						end
					else
						TweenService:Create(Slider.Main.Progress, TweenInfo.new(0.3, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Size = UDim2.new(0, Location - Slider.Main.AbsolutePosition.X > 5 and Location - Slider.Main.AbsolutePosition.X or 5, 1, 0)}):Play()
						Loop:Disconnect()
					end
				end)
			end)

			function SliderSettings:Set(NewVal)
				TweenService:Create(Slider.Main.Progress, TweenInfo.new(0.45, Enum.EasingStyle.Quint, Enum.EasingDirection.Out), {Size = UDim2.new(0, Slider.Main.AbsoluteSize.X * ((NewVal + SliderSettings.Range[1]) / (SliderSettings.Range[2] - SliderSettings.Range[1])) > 5 and Slider.Main.AbsoluteSize.X * (NewVal / (SliderSettings.Range[2] - SliderSettings.Range[1])) or 5, 1, 0)}):Play()
				Slider.Main.Information.Text = tostring(NewVal) .. " " .. SliderSettings.Suffix
				local Success, Response = pcall(function()
					SliderSettings.Callback(NewVal)
				end)
				if not Success then
					TweenService:Create(Slider, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = Color3.fromRGB(85, 0, 0)}):Play()
					TweenService:Create(Slider.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 1}):Play()
					Slider.Title.Text = "Callback Error"
					print("Rayfield | "..SliderSettings.Name.." Callback Error " ..tostring(Response))
					wait(0.5)
					Slider.Title.Text = SliderSettings.Name
					TweenService:Create(Slider, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {BackgroundColor3 = SelectedTheme.ElementBackground}):Play()
					TweenService:Create(Slider.UIStroke, TweenInfo.new(0.6, Enum.EasingStyle.Quint), {Transparency = 0}):Play()
				end
				SliderSettings.CurrentValue = NewVal
				SaveConfiguration()
			end
			if Settings.ConfigurationSaving then
				if Settings.ConfigurationSaving.Enabled and SliderSettings.Flag then
					RayfieldLibrary.Flags[SliderSettings.Flag] = SliderSettings
				end
			end
			return SliderSettings
		end


		return Tab
	end

	Elements.Visible = true

	wait(0.7)
	TweenService:Create(LoadingFrame.Title, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
	TweenService:Create(LoadingFrame.Subtitle, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
	TweenService:Create(LoadingFrame.Version, TweenInfo.new(0.5, Enum.EasingStyle.Quint), {TextTransparency = 1}):Play()
	wait(0.2)
	TweenService:Create(Main, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {Size = UDim2.new(0, 500, 0, 475)}):Play()
	TweenService:Create(Main.Shadow.Image, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.4}):Play()

	Topbar.BackgroundTransparency = 1
	Topbar.Divider.Size = UDim2.new(0, 0, 0, 1)
	Topbar.CornerRepair.BackgroundTransparency = 1
	Topbar.Title.TextTransparency = 1
	Topbar.Theme.ImageTransparency = 1
	Topbar.ChangeSize.ImageTransparency = 1
	Topbar.Hide.ImageTransparency = 1

	wait(0.5)
	Topbar.Visible = true
	TweenService:Create(Topbar, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	TweenService:Create(Topbar.CornerRepair, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {BackgroundTransparency = 0}):Play()
	wait(0.1)
	TweenService:Create(Topbar.Divider, TweenInfo.new(1, Enum.EasingStyle.Quint), {Size = UDim2.new(1, 0, 0, 1)}):Play()
	wait(0.1)
	TweenService:Create(Topbar.Title, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {TextTransparency = 0}):Play()
	wait(0.1)
	TweenService:Create(Topbar.Theme, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.8}):Play()
	wait(0.1)
	TweenService:Create(Topbar.ChangeSize, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.8}):Play()
	wait(0.1)
	TweenService:Create(Topbar.Hide, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.8}):Play()
	wait(0.3)

	return Window
end


function RayfieldLibrary:Destroy()
	Rayfield:Destroy()
end

Topbar.ChangeSize.MouseButton1Click:Connect(function()
	if Debounce then return end
	if Minimised then
		Minimised = false
		Maximise()
	else
		Minimised = true
		Minimise()
	end
end)

Topbar.Hide.MouseButton1Click:Connect(function()
	if Debounce then return end
	if Hidden then
		Hidden = false
		Minimised = false
		Unhide()
	else
		Hidden = true
		Hide()
	end
end)

UserInputService.InputBegan:Connect(function(input, processed)
	if (input.KeyCode == Enum.KeyCode.K and not processed) then
		if Debounce then return end
		if Hidden then
			Hidden = false
			Unhide()
		else
			Hidden = true
			Hide()
		end
	end
end)

for _, TopbarButton in ipairs(Topbar:GetChildren()) do
	if TopbarButton.ClassName == "ImageButton" then
		TopbarButton.MouseEnter:Connect(function()
			TweenService:Create(TopbarButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0}):Play()
		end)

		TopbarButton.MouseLeave:Connect(function()
			TweenService:Create(TopbarButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.8}):Play()
		end)

		TopbarButton.MouseButton1Click:Connect(function()
			TweenService:Create(TopbarButton, TweenInfo.new(0.7, Enum.EasingStyle.Quint), {ImageTransparency = 0.8}):Play()
		end)
	end
end


function RayfieldLibrary:LoadConfiguration()
	if CEnabled then
		pcall(function()
			if isfile(ConfigurationFolder .. "/" .. CFileName .. ConfigurationExtension) then
				LoadConfiguration(readfile(ConfigurationFolder .. "/" .. CFileName .. ConfigurationExtension))
				RayfieldLibrary:Notify({Title = "Configuration Loaded", Content = "The configuration file for this script has been loaded from a previous session"})
			end
		end)
	end
end

task.delay(3.5, RayfieldLibrary.LoadConfiguration, RayfieldLibrary)
if Rayfield:FindFirstChild("Notice") then
	Rayfield.Notice.Visible = true
	Rayfield.Notice.Interact.MouseButton1Click:Connect(function()
		Rayfield.Notice.Visible = false
	end)
end

	return RayfieldLibrary
]]


local auxLocal = [[ 

local aux = {}

local getGc = getgc
local getInfo = debug.getinfo or getinfo
local getUpvalue = debug.getupvalue or getupvalue or getupval
local getConstants = debug.getconstants or getconstants or getconsts
local isXClosure = is_synapse_function or issentinelclosure or is_protosmasher_closure or is_sirhurt_closure or istempleclosure or checkclosure
local isLClosure = islclosure or is_l_closure or (iscclosure and function(f) return not iscclosure(f) end)

assert(getGc and getInfo and getConstants and isXClosure, "Your exploit is not supported")

local placeholderUserdataConstant = newproxy(false)

local function matchConstants(closure, list)
    if not list then
        return true
    end
    
    local constants = getConstants(closure)
    
    for index, value in pairs(list) do
        if constants[index] ~= value and value ~= placeholderUserdataConstant then
            return false
        end
    end
    
    return true
end

local function searchClosure(script, name, upvalueIndex, constants)
    for _i, v in pairs(getGc()) do
        local parentScript = rawget(getfenv(v), "script")

        if type(v) == "function" and 
            isLClosure(v) and 
            not isXClosure(v) and 
            (
                (script == nil and parentScript.Parent == nil) or script == parentScript
            ) 
            and pcall(getUpvalue, v, upvalueIndex)
        then
            if ((name and name ~= "Unnamed function") and getInfo(v).name == name) and matchConstants(v, constants) then
                return v
            elseif (not name or name == "Unnamed function") and matchConstants(v, constants) then
                return v
            end
        end
    end
end

aux.placeholderUserdataConstant = placeholderUserdataConstant
aux.searchClosure = searchClosure

return aux

]]

local NofLibery = loadstring(NofLiberyLocal)()

DebugCheck(0,"Loaded!")

DebugCheck(0,"Anti AFK: Loaded!")

game:GetService("NetworkClient"):SetOutgoingKBPSLimit(math.huge)

_G.TeleportSpeed = 30


function TweenHello()
	local Notify = Instance.new("ScreenGui")
	local Background = Instance.new("Frame")
	local UICorner = Instance.new("UICorner")
	local Image = Instance.new("ImageLabel")
	local UICorner_2 = Instance.new("UICorner")
	local Label = Instance.new("TextLabel")
	local Text = Instance.new("TextLabel")
	local Line = Instance.new("Frame")

	local TweenService = game:GetService("TweenService")

	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quint, Enum.EasingDirection.Out)

	Background.Position = UDim2.new(-1, 0, 0.5, 0)

	local tween = TweenService:Create(Background, tweenInfo, {
		Position = UDim2.new(0.05, 0, 0.5, 0)
	})

	local function removeNotification()
		wait(3)
		tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
		local tweenOut = TweenService:Create(Background, tweenInfo, {
			Position = UDim2.new(-1, 0, 0.5, 0)
		})
		tweenOut:Play()
		wait(1)
		Notify:Destroy()
	end


	Notify.Name = "Notify"
	Notify.Parent = game:GetService("CoreGui")
	Notify.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

	Background.Name = "Background"
	Background.Parent = Notify
	Background.BackgroundColor3 = Color3.fromRGB(6, 5, 35)
	Background.Position = UDim2.new(0.05, 0, 0.5, 0)
	Background.Size = UDim2.new(0, 240, 0, 70)

	UICorner.CornerRadius = UDim.new(0, 15)
	UICorner.Parent = Background

	Image.Name = "Image"
	Image.Parent = Background
	Image.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Image.BorderSizePixel = 0
	Image.Position = UDim2.new(0.0291666668, 0, 0.142857149, 0)
	Image.Size = UDim2.new(0, 50, 0, 50)
	Image.Image = "rbxassetid://12954693578"
	Image.ScaleType = Enum.ScaleType.Tile

	UICorner_2.Parent = Image

	Label.Name = "Label"
	Label.Parent = Background
	Label.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Label.BackgroundTransparency = 1.000
	Label.BorderSizePixel = 0
	Label.Position = UDim2.new(0.273145556, 0, 0, 0)
	Label.Size = UDim2.new(0, 167, 0, 35)
	Label.Font = Enum.Font.SourceSansBold
	Label.Text = "Neko Hub V4"
	Label.TextColor3 = Color3.fromRGB(255, 255, 255)
	Label.TextSize = 28.000

	Text.Name = "Text"
	Text.Parent = Background
	Text.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Text.BackgroundTransparency = 1.000
	Text.BorderSizePixel = 0
	Text.Position = UDim2.new(0.273145556, 0, 0.50957489, 0)
	Text.Size = UDim2.new(0, 167, 0, 24)
	Text.Font = Enum.Font.SourceSans
	Text.Text = "Welcome!"
	Text.TextColor3 = Color3.fromRGB(255, 255, 255)
	Text.TextSize = 23.000

	Line.Name = "Line"
	Line.Parent = Background
	Line.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Line.BackgroundTransparency = 0.300
	Line.BorderSizePixel = 0
	Line.Position = UDim2.new(0.237499997, 0, 0.5, 0)
	Line.Size = UDim2.new(0, 183, 0, 1)

	local TweenService = game:GetService("TweenService")

	local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quint, Enum.EasingDirection.Out)

	Background.Position = UDim2.new(-1, 0, 0.5, 0)

	local tween = TweenService:Create(Background, tweenInfo, {
		Position = UDim2.new(0.05, 0, 0.5, 0)
	})

	tween:Play()

	local soundId = "rbxassetid://4695797538"

	local sound = Instance.new("Sound")
	sound.Name = "MySound"
	sound.SoundId = soundId
	sound.Volume = 1
	sound.PlaybackSpeed = 1
	sound.Looped = false
	sound.Parent = game.Workspace

	sound:Play()

	local function removeNotification()
		wait(3)
		tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quint, Enum.EasingDirection.InOut)
		local tweenOut = TweenService:Create(Background, tweenInfo, {
			Position = UDim2.new(-1, 0, 0.5, 0)
		})
		tweenOut:Play()
		wait(1)
		Notify:Destroy()
	end

	removeNotification()
end


TweenHello()
local FluentLocal = [[
local a,b={{1,'ModuleScript',{'MainModule'},{{18,'ModuleScript',{'Creator'}},{28,'ModuleScript',{'Icons'}},{47,'ModuleScript',{'Themes'},{{50,'ModuleScript',{'Dark'}},{52,'ModuleScript',{'Light'}},{51,'ModuleScript',{'Darker'}},{53,'ModuleScript',{'Rose'}},{49,'ModuleScript',{'Aqua'}},{48,'ModuleScript',{'Amethyst'}}}},{19,'ModuleScript',{'Elements'},{{21,'ModuleScript',{'Colorpicker'}},{27,'ModuleScript',{'Toggle'}},{23,'ModuleScript',{'Input'}},{20,'ModuleScript',{'Button'}},{25,'ModuleScript',{'Paragraph'}},{22,'ModuleScript',{'Dropdown'}},{26,'ModuleScript',{'Slider'}},{24,'ModuleScript',{'Keybind'}}}},{29,'Folder',{'Packages'},{{30,'ModuleScript',{'Flipper'},{{33,'ModuleScript',{'GroupMotor'}},{46,'ModuleScript',{'isMotor.spec'}},{39,'ModuleScript',{'Signal'}},{40,'ModuleScript',{'Signal.spec'}},{45,'ModuleScript',{'isMotor'}},{36,'ModuleScript',{'Instant.spec'}},{44,'ModuleScript',{'Spring.spec'}},{42,'ModuleScript',{'SingleMotor.spec'}},{38,'ModuleScript',{'Linear.spec'}},{31,'ModuleScript',{'BaseMotor'}},{43,'ModuleScript',{'Spring'}},{35,'ModuleScript',{'Instant'}},{37,'ModuleScript',{'Linear'}},{41,'ModuleScript',{'SingleMotor'}},{34,'ModuleScript',{'GroupMotor.spec'}},{32,'ModuleScript',{'BaseMotor.spec'}}}}}},{2,'ModuleScript',{'Acrylic'},{{3,'ModuleScript',{'AcrylicBlur'}},{5,'ModuleScript',{'CreateAcrylic'}},{6,'ModuleScript',{'Utils'}},{4,'ModuleScript',{'AcrylicPaint'}}}},{7,'Folder',{'Components'},{{9,'ModuleScript',{'Button'}},{12,'ModuleScript',{'Notification'}},{13,'ModuleScript',{'Section'}},{17,'ModuleScript',{'Window'}},{14,'ModuleScript',{'Tab'}},{10,'ModuleScript',{'Dialog'}},{8,'ModuleScript',{'Assets'}},{16,'ModuleScript',{'TitleBar'}},{15,'ModuleScript',{'Textbox'}},{11,'ModuleScript',{'Element'}}}}}}}local aa={function()local c,d,e,f,g=b(1)local h,i,j,k,l,m=game:GetService'Lighting',game:GetService'RunService',game:GetService'Players'.LocalPlayer,game:GetService'UserInputService',game:GetService'TweenService',game:GetService'Workspace'.CurrentCamera local n,o=j:GetMouse(),d local p,q,r,s=e(o.Creator),e(o.Elements),e(o.Acrylic),o.Components local t,u,v=e(s.Notification),p.New,protectgui or(syn and syn.protect_gui)or function()end local w=u('ScreenGui',{Parent=i:IsStudio()and j.PlayerGui or game:GetService'CoreGui'})v(w)t:Init(w)local x={Version='1.1.0',OpenFrames={},Options={},Themes=e(o.Themes).Names,Window=nil,WindowFrame=nil,Unloaded=false,Theme='Dark',DialogOpen=false,UseAcrylic=false,Acrylic=false,Transparency=true,MinimizeKeybind=nil,MinimizeKey=Enum.KeyCode.LeftControl,GUI=w}function x.SafeCallback(y,z,...)if not z then return end local A,B=pcall(z,...)if not A then local C,D=B:find':%d+: 'if not D then return x:Notify{Title='Interface',Content='Callback error',SubContent=B,Duration=5}end return x:Notify{Title='Interface',Content='Callback error',SubContent=B:sub(D+1),Duration=5}end end function x.Round(y,z,A)if A==0 then return math.floor(z)end z=tostring(z)return z:find'%.'and tonumber(z:sub(1,z:find'%.'+A))or z end local y=e(o.Icons).assets function x.GetIcon(z,A)if A~=nil and y['lucide-'..A]then return y['lucide-'..A]end return nil end local z={}z.__index=z z.__namecall=function(A,B,...)return z[B](...)end for A,B in ipairs(q)do z['Add'..B.__type]=function(C,D,E)B.Container=C.Container B.Type=C.Type B.ScrollFrame=C.ScrollFrame B.Library=x return B:New(D,E)end end x.Elements=z function x.CreateWindow(C,D)assert(D.Title,'Window - Missing Title')if x.Window then print'You cannot create more than one window.'return end x.MinimizeKey=D.MinimizeKey x.UseAcrylic=D.Acrylic if D.Acrylic then r.init()end local E=e(s.Window){Parent=w,Size=D.Size,Title=D.Title,SubTitle=D.SubTitle,TabWidth=D.TabWidth}x.Window=E x:SetTheme(D.Theme)return E end function x.SetTheme(C,D)if x.Window and table.find(x.Themes,D)then x.Theme=D p.UpdateTheme()end end function x.Destroy(C)if x.Window then x.Unloaded=true if x.UseAcrylic then x.Window.AcrylicPaint.Model:Destroy()end p.Disconnect()x.GUI:Destroy()end end function x.ToggleAcrylic(C,D)if x.Window then if x.UseAcrylic then x.Acrylic=D x.Window.AcrylicPaint.Model.Transparency=D and 0.98 or 1 if D then r.Enable()else r.Disable()end end end end function x.ToggleTransparency(C,D)if x.Window then x.Window.AcrylicPaint.Frame.Background.BackgroundTransparency=D and 0.35 or 0 end end function x.Notify(C,D)return t:New(D)end if getgenv then getgenv().Fluent=x end return x end,function()local c,d,e,f,g=b(2)local h={AcrylicBlur=e(d.AcrylicBlur),CreateAcrylic=e(d.CreateAcrylic),AcrylicPaint=e(d.AcrylicPaint)}function h.init()local i=Instance.new'DepthOfFieldEffect'i.FarIntensity=0 i.InFocusRadius=0.1 i.NearIntensity=1 local j={}function h.Enable()for k,l in pairs(j)do l.Enabled=false end i.Parent=game:GetService'Lighting'end function h.Disable()for k,l in pairs(j)do l.Enabled=l.enabled end i.Parent=nil end local k=function()local k=function(k)if k:IsA'DepthOfFieldEffect'then j[k]={enabled=k.Enabled}end end for l,m in pairs(game:GetService'Lighting':GetChildren())do k(m)end if game:GetService'Workspace'.CurrentCamera then for n,o in pairs(game:GetService'Workspace'.CurrentCamera:GetChildren())do k(o)end end end k()h.Enable()end return h end,function()local c,d,e,f,g=b(3)local h,i,j,k=e(d.Parent.Parent.Creator),e(d.Parent.CreateAcrylic),unpack(e(d.Parent.Utils))local l=function(l)local m={}l=l or 0.001 local n,o={topLeft=Vector2.new(),topRight=Vector2.new(),bottomRight=Vector2.new()},i()o.Parent=workspace local p,q=function(p,q)n.topLeft=q n.topRight=q+Vector2.new(p.X,0)n.bottomRight=q+p end,function()local p=game:GetService'Workspace'.CurrentCamera if p then p=p.CFrame end local q=p if not q then q=CFrame.new()end local r,s,t,u=q,n.topLeft,n.topRight,n.bottomRight local v,w,x=j(s,l),j(t,l),j(u,l)local y,z=(w-v).Magnitude,(w-x).Magnitude o.CFrame=CFrame.fromMatrix((v+x)/2,r.XVector,r.YVector,r.ZVector)o.Mesh.Scale=Vector3.new(y,z,0)end local r,s=function(r)local s=k()local t,u=r.AbsoluteSize-Vector2.new(s,s),r.AbsolutePosition+Vector2.new(s/2,s/2)p(t,u)task.spawn(q)end,function()local r=game:GetService'Workspace'.CurrentCamera if not r then return end table.insert(m,r:GetPropertyChangedSignal'CFrame':Connect(q))table.insert(m,r:GetPropertyChangedSignal'ViewportSize':Connect(q))table.insert(m,r:GetPropertyChangedSignal'FieldOfView':Connect(q))task.spawn(q)end o.Destroying:Connect(function()for t,u in m do pcall(function()u:Disconnect()end)end end)s()return r,o end return function(m)local n,o,p={},l(m)local q=h.New('Frame',{BackgroundTransparency=1,Size=UDim2.fromScale(1,1)})h.AddSignal(q:GetPropertyChangedSignal'AbsolutePosition',function()o(q)end)h.AddSignal(q:GetPropertyChangedSignal'AbsoluteSize',function()o(q)end)n.AddParent=function(r)h.AddSignal(r:GetPropertyChangedSignal'Visible',function()n.SetVisibility(r.Visible)end)end n.SetVisibility=function(r)p.Transparency=r and 0.98 or 1 end n.Frame=q n.Model=p return n end end,function()local c,d,e,f,g=b(4)local h,i=e(d.Parent.Parent.Creator),e(d.Parent.AcrylicBlur)local j=h.New return function(k)local l={}l.Frame=j('Frame',{Size=UDim2.fromScale(1,1),BackgroundTransparency=0.9,BackgroundColor3=Color3.fromRGB(255,255,255),BorderSizePixel=0},{j('ImageLabel',{Image='rbxassetid://8992230677',ScaleType='Slice',SliceCenter=Rect.new(Vector2.new(99,99),Vector2.new(99,99)),AnchorPoint=Vector2.new(0.5,0.5),Size=UDim2.new(1,120,1,116),Position=UDim2.new(0.5,0,0.5,0),BackgroundTransparency=1,ImageColor3=Color3.fromRGB(0,0,0),ImageTransparency=0.7}),j('UICorner',{CornerRadius=UDim.new(0,8)}),j('Frame',{BackgroundTransparency=0.45,Size=UDim2.fromScale(1,1),Name='Background',ThemeTag={BackgroundColor3='AcrylicMain'}},{j('UICorner',{CornerRadius=UDim.new(0,8)})}),j('Frame',{BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=0.4,Size=UDim2.fromScale(1,1)},{j('UICorner',{CornerRadius=UDim.new(0,8)}),j('UIGradient',{Rotation=90,ThemeTag={Color='AcrylicGradient'}})}),j('ImageLabel',{Image='rbxassetid://9968344105',ImageTransparency=0.98,ScaleType=Enum.ScaleType.Tile,TileSize=UDim2.new(0,128,0,128),Size=UDim2.fromScale(1,1),BackgroundTransparency=1},{j('UICorner',{CornerRadius=UDim.new(0,8)})}),j('ImageLabel',{Image='rbxassetid://9968344227',ImageTransparency=0.9,ScaleType=Enum.ScaleType.Tile,TileSize=UDim2.new(0,128,0,128),Size=UDim2.fromScale(1,1),BackgroundTransparency=1,ThemeTag={ImageTransparency='AcrylicNoise'}},{j('UICorner',{CornerRadius=UDim.new(0,8)})}),j('Frame',{BackgroundTransparency=1,Size=UDim2.fromScale(1,1),ZIndex=2},{j('UICorner',{CornerRadius=UDim.new(0,8)}),j('UIStroke',{Transparency=0.5,Thickness=1,ThemeTag={Color='AcrylicBorder'}})})})local m if e(d.Parent.Parent).UseAcrylic then m=i()m.Frame.Parent=l.Frame l.Model=m.Model l.AddParent=m.AddParent l.SetVisibility=m.SetVisibility end return l end end,function()local c,d,e,f,g=b(5)local h=d.Parent.Parent local i=e(h.Creator)local j=function()local j=i.New('Part',{Name='Body',Color=Color3.new(0,0,0),Material=Enum.Material.Glass,Size=Vector3.new(1,1,0),Anchored=true,CanCollide=false,Locked=true,CastShadow=false,Transparency=0.98},{i.New('SpecialMesh',{MeshType=Enum.MeshType.Brick,Offset=Vector3.new(0,0,-1E-6)})})return j end return j end,function()local c,d,e,f,g=b(6)local h,i=function(h,i,j,k,l)return(h-i)*(l-k)/(j-i)+k end,function(h,i)local j=game:GetService'Workspace'.CurrentCamera:ScreenPointToRay(h.X,h.Y)return j.Origin+j.Direction*i end local j=function()local j=game:GetService'Workspace'.CurrentCamera.ViewportSize.Y return h(j,0,2560,8,56)end return{i,j}end,[8]=function()local c,d,e,f,g=b(8)return{Close='rbxassetid://9886659671',Min='rbxassetid://9886659276',Max='rbxassetid://9886659406',Restore='rbxassetid://9886659001'}end,[9]=function()local c,d,e,f,g=b(9)local h=d.Parent.Parent local i,j=e(h.Packages.Flipper),e(h.Creator)local k,l=j.New,i.Spring.new return function(m,n,o)o=o or false local p={}p.Title=k('TextLabel',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',TextColor3=Color3.fromRGB(200,200,200),TextSize=14,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,BackgroundColor3=Color3.fromRGB(255,255,255),AutomaticSize=Enum.AutomaticSize.Y,BackgroundTransparency=1,Size=UDim2.fromScale(1,1),ThemeTag={TextColor3='Text'}})p.HoverFrame=k('Frame',{Size=UDim2.fromScale(1,1),BackgroundTransparency=1,ThemeTag={BackgroundColor3='Hover'}},{k('UICorner',{CornerRadius=UDim.new(0,4)})})p.Frame=k('TextButton',{Size=UDim2.new(0,0,0,32),Parent=n,ThemeTag={BackgroundColor3='DialogButton'}},{k('UICorner',{CornerRadius=UDim.new(0,4)}),k('UIStroke',{ApplyStrokeMode=Enum.ApplyStrokeMode.Border,Transparency=0.65,ThemeTag={Color='DialogButtonBorder'}}),p.HoverFrame,p.Title})local q,r=j.SpringMotor(1,p.HoverFrame,'BackgroundTransparency',o)j.AddSignal(p.Frame.MouseEnter,function()r(0.97)end)j.AddSignal(p.Frame.MouseLeave,function()r(1)end)j.AddSignal(p.Frame.MouseButton1Down,function()r(1)end)j.AddSignal(p.Frame.MouseButton1Up,function()r(0.97)end)return p end end,[10]=function()local c,d,e,f,g=b(10)local h,i,j,k=game:GetService'UserInputService',game:GetService'Players'.LocalPlayer:GetMouse(),game:GetService'Workspace'.CurrentCamera,d.Parent.Parent local l,m=e(k.Packages.Flipper),e(k.Creator)local n,o,p,q=l.Spring.new,l.Instant.new,m.New,{Window=nil}function q.Init(r,s)q.Window=s return q end function q.Create(r)local s={Buttons=0}s.TintFrame=p('TextButton',{Text='',Size=UDim2.fromScale(1,1),BackgroundColor3=Color3.fromRGB(0,0,0),BackgroundTransparency=1,Parent=q.Window.Root},{p('UICorner',{CornerRadius=UDim.new(0,8)})})local t,u=m.SpringMotor(1,s.TintFrame,'BackgroundTransparency',true)s.ButtonHolder=p('Frame',{Size=UDim2.new(1,-40,1,-40),AnchorPoint=Vector2.new(0.5,0.5),Position=UDim2.fromScale(0.5,0.5),BackgroundTransparency=1},{p('UIListLayout',{Padding=UDim.new(0,10),FillDirection=Enum.FillDirection.Horizontal,HorizontalAlignment=Enum.HorizontalAlignment.Center,SortOrder=Enum.SortOrder.LayoutOrder})})s.ButtonHolderFrame=p('Frame',{Size=UDim2.new(1,0,0,70),Position=UDim2.new(0,0,1,-70),ThemeTag={BackgroundColor3='DialogHolder'}},{p('Frame',{Size=UDim2.new(1,0,0,1),ThemeTag={BackgroundColor3='DialogHolderLine'}}),s.ButtonHolder})s.Title=p('TextLabel',{FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.SemiBold,Enum.FontStyle.Normal),Text='Dialog',TextColor3=Color3.fromRGB(240,240,240),TextSize=22,TextXAlignment=Enum.TextXAlignment.Left,Size=UDim2.new(1,0,0,22),Position=UDim2.fromOffset(20,25),BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,ThemeTag={TextColor3='Text'}})s.Scale=p('UIScale',{Scale=1})local v,w=m.SpringMotor(1.1,s.Scale,'Scale')s.Root=p('CanvasGroup',{Size=UDim2.fromOffset(300,165),AnchorPoint=Vector2.new(0.5,0.5),Position=UDim2.fromScale(0.5,0.5),GroupTransparency=1,Parent=s.TintFrame,ThemeTag={BackgroundColor3='Dialog'}},{p('UICorner',{CornerRadius=UDim.new(0,8)}),p('UIStroke',{Transparency=0.5,ThemeTag={Color='DialogBorder'}}),s.Scale,s.Title,s.ButtonHolderFrame})local x,y=m.SpringMotor(1,s.Root,'GroupTransparency')function s.Open(z)e(k).DialogOpen=true s.Scale.Scale=1.1 u(0.75)y(0)w(1)end function s.Close(z)e(k).DialogOpen=false u(1)y(1)w(1.1)s.Root.UIStroke:Destroy()task.wait(0.15)s.TintFrame:Destroy()end function s.Button(z,A,B)s.Buttons=s.Buttons+1 A=A or'Button'B=B or function()end local C=e(k.Components.Button)('',s.ButtonHolder,true)C.Title.Text=A for D,E in next,s.ButtonHolder:GetChildren()do if E:IsA'TextButton'then E.Size=UDim2.new(1/s.Buttons,-(((s.Buttons-1)*10)/s.Buttons),0,32)end end m.AddSignal(C.Frame.MouseButton1Click,function()e(k):SafeCallback(B)pcall(function()s:Close()end)end)return C end return s end return q end,[11]=function()local c,d,e,f,g=b(11)local h=d.Parent.Parent local i,j=e(h.Packages.Flipper),e(h.Creator)local k,l=j.New,i.Spring.new return function(m,n,o,p)local q={}q.TitleLabel=k('TextLabel',{FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.Medium,Enum.FontStyle.Normal),Text=m,TextColor3=Color3.fromRGB(240,240,240),TextSize=13,TextXAlignment=Enum.TextXAlignment.Left,Size=UDim2.new(1,0,0,14),BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,ThemeTag={TextColor3='Text'}})q.DescLabel=k('TextLabel',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',Text=n,TextColor3=Color3.fromRGB(200,200,200),TextSize=12,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,BackgroundColor3=Color3.fromRGB(255,255,255),AutomaticSize=Enum.AutomaticSize.Y,BackgroundTransparency=1,Size=UDim2.new(1,0,0,14),ThemeTag={TextColor3='SubText'}})q.LabelHolder=k('Frame',{AutomaticSize=Enum.AutomaticSize.Y,BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,Position=UDim2.fromOffset(10,0),Size=UDim2.new(1,-28,0,0)},{k('UIListLayout',{SortOrder=Enum.SortOrder.LayoutOrder,VerticalAlignment=Enum.VerticalAlignment.Center}),k('UIPadding',{PaddingBottom=UDim.new(0,13),PaddingTop=UDim.new(0,13)}),q.TitleLabel,q.DescLabel})q.Border=k('UIStroke',{Transparency=0.5,ApplyStrokeMode=Enum.ApplyStrokeMode.Border,Color=Color3.fromRGB(0,0,0),ThemeTag={Color='ElementBorder'}})q.Frame=k('TextButton',{Size=UDim2.new(1,0,0,0),BackgroundTransparency=0.89,BackgroundColor3=Color3.fromRGB(130,130,130),Parent=o,AutomaticSize=Enum.AutomaticSize.Y,Text='',LayoutOrder=7,ThemeTag={BackgroundColor3='Element',BackgroundTransparency='ElementTransparency'}},{k('UICorner',{CornerRadius=UDim.new(0,4)}),q.Border,q.LabelHolder})function q.SetTitle(r,s)q.TitleLabel.Text=s end function q.SetDesc(r,s)if s==nil then s=''end if s==''then q.DescLabel.Visible=false else q.DescLabel.Visible=true end q.DescLabel.Text=s end function q.Destroy(r)q.Frame:Destroy()end q:SetTitle(m)q:SetDesc(n)if p then local r,s,t=h.Themes,j.SpringMotor(j.GetThemeProperty'ElementTransparency',q.Frame,'BackgroundTransparency',false,true)j.AddSignal(q.Frame.MouseEnter,function()t(j.GetThemeProperty'ElementTransparency'-j.GetThemeProperty'HoverChange')end)j.AddSignal(q.Frame.MouseLeave,function()t(j.GetThemeProperty'ElementTransparency')end)j.AddSignal(q.Frame.MouseButton1Down,function()t(j.GetThemeProperty'ElementTransparency'+j.GetThemeProperty'HoverChange')end)j.AddSignal(q.Frame.MouseButton1Up,function()t(j.GetThemeProperty'ElementTransparency'-j.GetThemeProperty'HoverChange')end)end return q end end,[12]=function()local c,d,e,f,g=b(12)local h=d.Parent.Parent local i,j,k=e(h.Packages.Flipper),e(h.Creator),e(h.Acrylic)local l,m,n,o=i.Spring.new,i.Instant.new,j.New,{}function o.Init(p,q)o.Holder=n('Frame',{Position=UDim2.new(1,-30,1,-30),Size=UDim2.new(0,310,1,-30),AnchorPoint=Vector2.new(1,1),BackgroundTransparency=1,Parent=q},{n('UIListLayout',{HorizontalAlignment=Enum.HorizontalAlignment.Center,SortOrder=Enum.SortOrder.LayoutOrder,VerticalAlignment=Enum.VerticalAlignment.Bottom,Padding=UDim.new(0,20)})})end function o.New(p,q)q.Title=q.Title or'Title'q.Content=q.Content or'Content'q.SubContent=q.SubContent or''q.Duration=q.Duration or nil q.Buttons=q.Buttons or{}local r={Closed=false}r.AcrylicPaint=k.AcrylicPaint()r.Title=n('TextLabel',{Position=UDim2.new(0,14,0,17),Text=q.Title,RichText=true,TextColor3=Color3.fromRGB(255,255,255),TextTransparency=0,FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',TextSize=13,TextXAlignment='Left',TextYAlignment='Center',Size=UDim2.new(1,-12,0,12),TextWrapped=true,BackgroundTransparency=1,ThemeTag={TextColor3='Text'}})r.ContentLabel=n('TextLabel',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',Text=q.Content,TextColor3=Color3.fromRGB(240,240,240),TextSize=14,TextXAlignment=Enum.TextXAlignment.Left,AutomaticSize=Enum.AutomaticSize.Y,Size=UDim2.new(1,0,0,14),BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,TextWrapped=true,ThemeTag={TextColor3='Text'}})r.SubContentLabel=n('TextLabel',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',Text=q.SubContent,TextColor3=Color3.fromRGB(240,240,240),TextSize=14,TextXAlignment=Enum.TextXAlignment.Left,AutomaticSize=Enum.AutomaticSize.Y,Size=UDim2.new(1,0,0,14),BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,TextWrapped=true,ThemeTag={TextColor3='SubText'}})r.LabelHolder=n('Frame',{AutomaticSize=Enum.AutomaticSize.Y,BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,Position=UDim2.fromOffset(14,40),Size=UDim2.new(1,-28,0,0)},{n('UIListLayout',{SortOrder=Enum.SortOrder.LayoutOrder,VerticalAlignment=Enum.VerticalAlignment.Center,Padding=UDim.new(0,3)}),r.ContentLabel,r.SubContentLabel})r.CloseButton=n('TextButton',{Text='',Position=UDim2.new(1,-14,0,13),Size=UDim2.fromOffset(20,20),AnchorPoint=Vector2.new(1,0),BackgroundTransparency=1},{n('ImageLabel',{Image=e(d.Parent.Assets).Close,Size=UDim2.fromOffset(16,16),Position=UDim2.fromScale(0.5,0.5),AnchorPoint=Vector2.new(0.5,0.5),BackgroundTransparency=1,ThemeTag={ImageColor3='Text'}})})r.Root=n('Frame',{BackgroundTransparency=1,Size=UDim2.new(1,0,1,0),Position=UDim2.fromScale(1,0)},{r.AcrylicPaint.Frame,r.Title,r.CloseButton,r.LabelHolder})if q.Content==''then r.ContentLabel.Visible=false end if q.SubContent==''then r.SubContentLabel.Visible=false end r.Holder=n('Frame',{BackgroundTransparency=1,Size=UDim2.new(1,0,0,200),Parent=o.Holder},{r.Root})local s=i.GroupMotor.new{Scale=1,Offset=60}s:onStep(function(t)r.Root.Position=UDim2.new(t.Scale,t.Offset,0,0)end)j.AddSignal(r.CloseButton.MouseButton1Click,function()r:Close()end)function r.Open(t)local u=r.LabelHolder.AbsoluteSize.Y r.Holder.Size=UDim2.new(1,0,0,58+u)s:setGoal{Scale=l(0,{frequency=5}),Offset=l(0,{frequency=5})}end function r.Close(t)if not r.Closed then r.Closed=true task.spawn(function()s:setGoal{Scale=l(1,{frequency=5}),Offset=l(60,{frequency=5})}task.wait(0.4)if e(h).UseAcrylic then r.AcrylicPaint.Model:Destroy()end r.Holder:Destroy()end)end end r:Open()if q.Duration then task.delay(q.Duration,function()r:Close()end)end return r end return o end,[13]=function()local c,d,e,f,g=b(13)local h=d.Parent.Parent local i=e(h.Creator)local j=i.New return function(k,l)local m={}m.Layout=j('UIListLayout',{Padding=UDim.new(0,5)})m.Container=j('Frame',{Size=UDim2.new(1,0,0,26),Position=UDim2.fromOffset(0,24),BackgroundTransparency=1},{m.Layout})m.Root=j('Frame',{BackgroundTransparency=1,Size=UDim2.new(1,0,0,26),LayoutOrder=7,Parent=l},{j('TextLabel',{RichText=true,Text=k,TextTransparency=0,FontFace=Font.new('rbxassetid://12187365364',Enum.FontWeight.SemiBold,Enum.FontStyle.Normal),TextSize=18,TextXAlignment='Left',TextYAlignment='Center',Size=UDim2.new(1,-16,0,18),Position=UDim2.fromOffset(0,2),ThemeTag={TextColor3='Text'}}),m.Container})i.AddSignal(m.Layout:GetPropertyChangedSignal'AbsoluteContentSize',function()m.Container.Size=UDim2.new(1,0,0,m.Layout.AbsoluteContentSize.Y)m.Root.Size=UDim2.new(1,0,0,m.Layout.AbsoluteContentSize.Y+25)end)return m end end,[14]=function()local c,d,e,f,g=b(14)local h=d.Parent.Parent local i,j=e(h.Packages.Flipper),e(h.Creator)local k,l,m,n,o=j.New,i.Spring.new,i.Instant.new,h.Components,{Window=nil,Tabs={},Containers={},SelectedTab=0,TabCount=0}function o.Init(p,q)o.Window=q return o end function o.GetCurrentTabPos(p)local q,r=o.Window.TabHolder.AbsolutePosition.Y,o.Tabs[o.SelectedTab].Frame.AbsolutePosition.Y return r-q end function o.New(p,q,r,s)local t,u=e(h),o.Window local v=t.Elements o.TabCount=o.TabCount+1 local w,x=o.TabCount,{Selected=false,Name=q,Type='Tab'}if t:GetIcon(r)then r=t:GetIcon(r)end if r==''or nil then r=nil end x.Frame=k('TextButton',{Size=UDim2.new(1,0,0,34),BackgroundTransparency=1,Parent=s,ThemeTag={BackgroundColor3='Tab'}},{k('UICorner',{CornerRadius=UDim.new(0,6)}),k('TextLabel',{AnchorPoint=Vector2.new(0,0.5),Position=r and UDim2.new(0,30,0.5,0)or UDim2.new(0,12,0.5,0),Text=q,RichText=true,TextColor3=Color3.fromRGB(255,255,255),TextTransparency=0,FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.Regular,Enum.FontStyle.Normal),TextSize=12,TextXAlignment='Left',TextYAlignment='Center',Size=UDim2.new(1,-12,1,0),BackgroundTransparency=1,ThemeTag={TextColor3='Text'}}),k('ImageLabel',{AnchorPoint=Vector2.new(0,0.5),Size=UDim2.fromOffset(16,16),Position=UDim2.new(0,8,0.5,0),BackgroundTransparency=1,Image=r and r or nil,ThemeTag={ImageColor3='Text'}})})local y=k('UIListLayout',{Padding=UDim.new(0,5),SortOrder=Enum.SortOrder.LayoutOrder})x.ContainerFrame=k('ScrollingFrame',{Size=UDim2.fromScale(1,1),BackgroundTransparency=1,Parent=u.ContainerHolder,Visible=false,BottomImage='rbxassetid://6889812791',MidImage='rbxassetid://6889812721',TopImage='rbxassetid://6276641225',ScrollBarImageColor3=Color3.fromRGB(255,255,255),ScrollBarImageTransparency=0.95,ScrollBarThickness=3,BorderSizePixel=0,CanvasSize=UDim2.fromScale(0,0),ScrollingDirection=Enum.ScrollingDirection.Y},{y,k('UIPadding',{PaddingRight=UDim.new(0,10),PaddingLeft=UDim.new(0,1),PaddingTop=UDim.new(0,1),PaddingBottom=UDim.new(0,1)})})j.AddSignal(y:GetPropertyChangedSignal'AbsoluteContentSize',function()x.ContainerFrame.CanvasSize=UDim2.new(0,0,0,y.AbsoluteContentSize.Y+2)end)x.Motor,x.SetTransparency=j.SpringMotor(1,x.Frame,'BackgroundTransparency')j.AddSignal(x.Frame.MouseEnter,function()x.SetTransparency(x.Selected and 0.85 or 0.89)end)j.AddSignal(x.Frame.MouseLeave,function()x.SetTransparency(x.Selected and 0.89 or 1)end)j.AddSignal(x.Frame.MouseButton1Down,function()x.SetTransparency(0.92)end)j.AddSignal(x.Frame.MouseButton1Up,function()x.SetTransparency(x.Selected and 0.85 or 0.89)end)j.AddSignal(x.Frame.MouseButton1Click,function()o:SelectTab(w)end)o.Containers[w]=x.ContainerFrame o.Tabs[w]=x x.Container=x.ContainerFrame x.ScrollFrame=x.Container function x.AddSection(z,A)local B,C={Type='Section'},e(n.Section)(A,x.Container)B.Container=C.Container B.ScrollFrame=x.Container setmetatable(B,v)return B end setmetatable(x,v)return x end function o.SelectTab(p,q)local r=o.Window o.SelectedTab=q for s,t in next,o.Tabs do t.SetTransparency(1)t.Selected=false end o.Tabs[q].SetTransparency(0.89)o.Tabs[q].Selected=true r.TabDisplay.Text=o.Tabs[q].Name r.SelectorPosMotor:setGoal(l(o:GetCurrentTabPos(),{frequency=6}))task.spawn(function()r.ContainerPosMotor:setGoal(l(110,{frequency=10}))r.ContainerBackMotor:setGoal(l(1,{frequency=10}))task.wait(0.15)for u,v in next,o.Containers do v.Visible=false end o.Containers[q].Visible=true r.ContainerPosMotor:setGoal(l(94,{frequency=5}))r.ContainerBackMotor:setGoal(l(0,{frequency=8}))end)end return o end,[15]=function()local c,d,e,f,g=b(15)local h,i=game:GetService'TextService',d.Parent.Parent local j,k=e(i.Packages.Flipper),e(i.Creator)local l=k.New return function(m,n)n=n or false local o={}o.Input=l('TextBox',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',TextColor3=Color3.fromRGB(200,200,200),TextSize=14,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,BackgroundColor3=Color3.fromRGB(255,255,255),AutomaticSize=Enum.AutomaticSize.Y,BackgroundTransparency=1,Size=UDim2.fromScale(1,1),Position=UDim2.fromOffset(10,0),ThemeTag={TextColor3='Text',PlaceholderColor3='SubText'}})o.Container=l('Frame',{BackgroundTransparency=1,ClipsDescendants=true,Position=UDim2.new(0,6,0,0),Size=UDim2.new(1,-12,1,0)},{o.Input})o.Indicator=l('Frame',{Size=UDim2.new(1,-4,0,1),Position=UDim2.new(0,2,1,0),AnchorPoint=Vector2.new(0,1),BackgroundTransparency=n and 0.5 or 0,ThemeTag={BackgroundColor3=n and'InputIndicator'or'DialogInputLine'}})o.Frame=l('Frame',{Size=UDim2.new(0,0,0,30),BackgroundTransparency=n and 0.9 or 0,Parent=m,ThemeTag={BackgroundColor3=n and'Input'or'DialogInput'}},{l('UICorner',{CornerRadius=UDim.new(0,4)}),l('UIStroke',{ApplyStrokeMode=Enum.ApplyStrokeMode.Border,Transparency=n and 0.5 or 0.65,ThemeTag={Color=n and'InElementBorder'or'DialogButtonBorder'}}),o.Indicator,o.Container})local p=function()local p,q=2,o.Container.AbsoluteSize.X if not o.Input:IsFocused()or o.Input.TextBounds.X<=q-2*p then o.Input.Position=UDim2.new(0,p,0,0)else local r=o.Input.CursorPosition if r~=-1 then local s=string.sub(o.Input.Text,1,r-1)local t=h:GetTextSize(s,o.Input.TextSize,o.Input.Font,Vector2.new(math.huge,math.huge)).X local u=o.Input.Position.X.Offset+t if u<p then o.Input.Position=UDim2.fromOffset(p-t,0)elseif u>q-p-1 then o.Input.Position=UDim2.fromOffset(q-t-p-1,0)end end end end task.spawn(p)k.AddSignal(o.Input:GetPropertyChangedSignal'Text',p)k.AddSignal(o.Input:GetPropertyChangedSignal'CursorPosition',p)k.AddSignal(o.Input.Focused,function()p()o.Indicator.Size=UDim2.new(1,-2,0,2)o.Indicator.Position=UDim2.new(0,1,1,0)o.Indicator.BackgroundTransparency=0 k.OverrideTag(o.Frame,{BackgroundColor3=n and'InputFocused'or'DialogHolder'})k.OverrideTag(o.Indicator,{BackgroundColor3='Accent'})end)k.AddSignal(o.Input.FocusLost,function()p()o.Indicator.Size=UDim2.new(1,-4,0,1)o.Indicator.Position=UDim2.new(0,2,1,0)o.Indicator.BackgroundTransparency=0.5 k.OverrideTag(o.Frame,{BackgroundColor3=n and'Input'or'DialogInput'})k.OverrideTag(o.Indicator,{BackgroundColor3=n and'InputIndicator'or'DialogInputLine'})end)return o end end,[16]=function()local c,d,e,f,g=b(16)local h,i=d.Parent.Parent,e(d.Parent.Assets)local j,k=e(h.Creator),e(h.Packages.Flipper)local l,m=j.New,j.AddSignal return function(n)local o,p,q={},e(h),function(o,p,q,r)local s={Callback=r or function()end}s.Frame=l('TextButton',{Size=UDim2.new(0,34,1,-8),AnchorPoint=Vector2.new(1,0),BackgroundTransparency=1,Parent=q,Position=p,Text='',ThemeTag={BackgroundColor3='Text'}},{l('UICorner',{CornerRadius=UDim.new(0,7)}),l('ImageLabel',{Image=o,Size=UDim2.fromOffset(16,16),Position=UDim2.fromScale(0.5,0.5),AnchorPoint=Vector2.new(0.5,0.5),BackgroundTransparency=1,Name='Icon',ThemeTag={ImageColor3='Text'}})})local t,u=j.SpringMotor(1,s.Frame,'BackgroundTransparency')m(s.Frame.MouseEnter,function()u(0.94)end)m(s.Frame.MouseLeave,function()u(1,true)end)m(s.Frame.MouseButton1Down,function()u(0.96)end)m(s.Frame.MouseButton1Up,function()u(0.94)end)m(s.Frame.MouseButton1Click,s.Callback)s.SetCallback=function(v)s.Callback=v end return s end o.Frame=l('Frame',{Size=UDim2.new(1,0,0,42),BackgroundTransparency=1,Parent=n.Parent},{l('Frame',{Size=UDim2.new(1,-16,1,0),Position=UDim2.new(0,16,0,0),BackgroundTransparency=1},{l('UIListLayout',{Padding=UDim.new(0,5),FillDirection=Enum.FillDirection.Horizontal,SortOrder=Enum.SortOrder.LayoutOrder}),l('TextLabel',{RichText=true,Text=n.Title,FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.Regular,Enum.FontStyle.Normal),TextSize=12,TextXAlignment='Left',TextYAlignment='Center',Size=UDim2.fromScale(0,1),AutomaticSize=Enum.AutomaticSize.X,BackgroundTransparency=1,ThemeTag={TextColor3='Text'}}),l('TextLabel',{RichText=true,Text=n.SubTitle,TextTransparency=0.4,FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.Regular,Enum.FontStyle.Normal),TextSize=12,TextXAlignment='Left',TextYAlignment='Center',Size=UDim2.fromScale(0,1),AutomaticSize=Enum.AutomaticSize.X,BackgroundTransparency=1,ThemeTag={TextColor3='Text'}})}),l('Frame',{BackgroundTransparency=0.5,Size=UDim2.new(1,0,0,1),Position=UDim2.new(0,0,1,0),ThemeTag={BackgroundColor3='TitleBarLine'}})})o.CloseButton=q(i.Close,UDim2.new(1,-4,0,4),o.Frame,function()p.Window:Dialog{Title='Close',Content='Are you sure you want to unload the interface?',Buttons={{Title='Yes',Callback=function()p:Destroy()end},{Title='No'}}}end)o.MaxButton=q(i.Max,UDim2.new(1,-40,0,4),o.Frame,function()n.Window.Maximize(not n.Window.Maximized)end)o.MinButton=q(i.Min,UDim2.new(1,-80,0,4),o.Frame,function()p.Window:Minimize()end)return o end end,[17]=function()local c,d,e,f,g=b(17)local h,i,j,k=game:GetService'UserInputService',game:GetService'Players'.LocalPlayer:GetMouse(),game:GetService'Workspace'.CurrentCamera,d.Parent.Parent local l,m,n,o,p=e(k.Packages.Flipper),e(k.Creator),e(k.Acrylic),e(d.Parent.Assets),d.Parent local q,r,s=l.Spring.new,l.Instant.new,m.New return function(t)local u,v,w,x,y,z=e(k),{Minimized=false,Maximized=false,Size=t.Size,CurrentPos=0,Position=UDim2.fromOffset(j.ViewportSize.X/2-t.Size.X.Offset/2,j.ViewportSize.Y/2-t.Size.Y.Offset/2)},false local A,B=false local C=false v.AcrylicPaint=n.AcrylicPaint()local D,E=s('Frame',{Size=UDim2.fromOffset(4,0),BackgroundColor3=Color3.fromRGB(76,194,255),Position=UDim2.fromOffset(0,17),AnchorPoint=Vector2.new(0,0.5),ThemeTag={BackgroundColor3='Accent'}},{s('UICorner',{CornerRadius=UDim.new(0,2)})}),s('Frame',{Size=UDim2.fromOffset(20,20),BackgroundTransparency=1,Position=UDim2.new(1,-20,1,-20)})v.TabHolder=s('ScrollingFrame',{Size=UDim2.fromScale(1,1),BackgroundTransparency=1,ScrollBarImageTransparency=1,ScrollBarThickness=0,BorderSizePixel=0,CanvasSize=UDim2.fromScale(0,0),ScrollingDirection=Enum.ScrollingDirection.Y},{s('UIListLayout',{Padding=UDim.new(0,4)})})local F=s('Frame',{Size=UDim2.new(0,t.TabWidth,1,-66),Position=UDim2.new(0,12,0,54),BackgroundTransparency=1,ClipsDescendants=true},{v.TabHolder,D})v.TabDisplay=s('TextLabel',{RichText=true,Text='Tab',TextTransparency=0,FontFace=Font.new('rbxassetid://12187365364',Enum.FontWeight.SemiBold,Enum.FontStyle.Normal),TextSize=28,TextXAlignment='Left',TextYAlignment='Center',Size=UDim2.new(1,-16,0,28),Position=UDim2.fromOffset(t.TabWidth+26,56),BackgroundTransparency=1,ThemeTag={TextColor3='Text'}})v.ContainerHolder=s('CanvasGroup',{Size=UDim2.new(1,-t.TabWidth-32,1,-102),Position=UDim2.fromOffset(t.TabWidth+26,90),BackgroundTransparency=1})v.Root=s('Frame',{BackgroundTransparency=1,Size=v.Size,Position=v.Position,Parent=t.Parent},{v.AcrylicPaint.Frame,v.TabDisplay,v.ContainerHolder,F,E})v.TitleBar=e(d.Parent.TitleBar){Title=t.Title,SubTitle=t.SubTitle,Parent=v.Root,Window=v}if e(k).UseAcrylic then v.AcrylicPaint.AddParent(v.Root)end local G,H=l.GroupMotor.new{X=v.Size.X.Offset,Y=v.Size.Y.Offset},l.GroupMotor.new{X=v.Position.X.Offset,Y=v.Position.Y.Offset}v.SelectorPosMotor=l.SingleMotor.new(17)v.SelectorSizeMotor=l.SingleMotor.new(0)v.ContainerBackMotor=l.SingleMotor.new(0)v.ContainerPosMotor=l.SingleMotor.new(94)G:onStep(function(I)v.Root.Size=UDim2.new(0,I.X,0,I.Y)end)H:onStep(function(I)v.Root.Position=UDim2.new(0,I.X,0,I.Y)end)local I,J=0,0 v.SelectorPosMotor:onStep(function(K)D.Position=UDim2.new(0,0,0,K+17)local L=tick()local M=L-J if I~=nil then v.SelectorSizeMotor:setGoal(q((math.abs(K-I)/(M*60))+16))I=K end J=L end)v.SelectorSizeMotor:onStep(function(K)D.Size=UDim2.new(0,4,0,K)end)v.ContainerBackMotor:onStep(function(K)v.ContainerHolder.GroupTransparency=K end)v.ContainerPosMotor:onStep(function(K)v.ContainerHolder.Position=UDim2.fromOffset(t.TabWidth+26,K)end)local K,L v.Maximize=function(M,N,O)v.Maximized=M v.TitleBar.MaxButton.Frame.Icon.Image=M and o.Restore or o.Max if M then K=v.Size.X.Offset L=v.Size.Y.Offset end local P,Q=M and j.ViewportSize.X or K,M and j.ViewportSize.Y or L G:setGoal{X=l[O and'Instant'or'Spring'].new(P,{frequency=6}),Y=l[O and'Instant'or'Spring'].new(Q,{frequency=6})}v.Size=UDim2.fromOffset(P,Q)if not N then H:setGoal{X=q(M and 0 or v.Position.X.Offset,{frequency=6}),Y=q(M and 0 or v.Position.Y.Offset,{frequency=6})}end end m.AddSignal(v.TitleBar.Frame.InputBegan,function(M)if M.UserInputType==Enum.UserInputType.MouseButton1 or M.UserInputType==Enum.UserInputType.Touch then w=true y=M.Position z=v.Root.Position if v.Maximized then z=UDim2.fromOffset(i.X-(i.X*((K-100)/v.Root.AbsoluteSize.X)),i.Y-(i.Y*(L/v.Root.AbsoluteSize.Y)))end M.Changed:Connect(function()if M.UserInputState==Enum.UserInputState.End then w=false end end)end end)m.AddSignal(v.TitleBar.Frame.InputChanged,function(M)if M.UserInputType==Enum.UserInputType.MouseMovement or M.UserInputType==Enum.UserInputType.Touch then x=M end end)m.AddSignal(E.InputBegan,function(M)if M.UserInputType==Enum.UserInputType.MouseButton1 or M.UserInputType==Enum.UserInputType.Touch then A=true B=M.Position end end)m.AddSignal(h.InputChanged,function(M)if M==x and w then local N=M.Position-y v.Position=UDim2.fromOffset(z.X.Offset+N.X,z.Y.Offset+N.Y)H:setGoal{X=r(v.Position.X.Offset),Y=r(v.Position.Y.Offset)}if v.Maximized then v.Maximize(false,true,true)end end if(M.UserInputType==Enum.UserInputType.MouseMovement or M.UserInputType==Enum.UserInputType.Touch)and A then local N,O=M.Position-B,v.Size local P=Vector3.new(O.X.Offset,O.Y.Offset,0)+Vector3.new(1,1,0)*N local Q=Vector2.new(math.clamp(P.X,470,2048),math.clamp(P.Y,380,2048))G:setGoal{X=l.Instant.new(Q.X),Y=l.Instant.new(Q.Y)}end end)m.AddSignal(h.InputEnded,function(M)if A==true or M.UserInputType==Enum.UserInputType.Touch then A=false v.Size=UDim2.fromOffset(G:getValue().X,G:getValue().Y)end end)m.AddSignal(v.TabHolder.UIListLayout:GetPropertyChangedSignal'AbsoluteContentSize',function()v.TabHolder.CanvasSize=UDim2.new(0,0,0,v.TabHolder.UIListLayout.AbsoluteContentSize.Y)end)m.AddSignal(h.InputBegan,function(M)if type(u.MinimizeKeybind)=='table'and u.MinimizeKeybind.Type=='Keybind'and not h:GetFocusedTextBox()then if M.KeyCode.Name==u.MinimizeKeybind.Value then v:Minimize()end elseif M.KeyCode==u.MinimizeKey and not h:GetFocusedTextBox()then v:Minimize()end end)function v.Minimize(M)v.Minimized=not v.Minimized v.Root.Visible=not v.Minimized if not C then C=true local N=u.MinimizeKeybind and u.MinimizeKeybind.Value or u.MinimizeKey.Name u:Notify{Title='Interface',Content='Press '..N..' to toggle the inteface.',Duration=6}end end function v.Destroy(M)if e(k).UseAcrylic then v.AcrylicPaint.Model:Destroy()end v.Root:Destroy()end local M=e(p.Dialog):Init(v)function v.Dialog(N,O)local P=M:Create()P.Title.Text=O.Title local Q=s('TextLabel',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',Text=O.Content,TextColor3=Color3.fromRGB(240,240,240),TextSize=14,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Top,Size=UDim2.new(1,-40,1,0),Position=UDim2.fromOffset(20,60),BackgroundTransparency=1,Parent=P.Root,ClipsDescendants=false,ThemeTag={TextColor3='Text'}})s('UISizeConstraint',{MinSize=Vector2.new(300,165),MaxSize=Vector2.new(620,math.huge),Parent=P.Root})P.Root.Size=UDim2.fromOffset(Q.TextBounds.X+40,165)if Q.TextBounds.X+40>v.Size.X.Offset-120 then P.Root.Size=UDim2.fromOffset(v.Size.X.Offset-120,165)Q.TextWrapped=true P.Root.Size=UDim2.fromOffset(v.Size.X.Offset-120,Q.TextBounds.Y+150)end for R,S in next,O.Buttons do P:Button(S.Title,S.Callback)end P:Open()end local N=e(p.Tab):Init(v)function v.AddTab(O,P)return N:New(P.Title,P.Icon,v.TabHolder)end function v.SelectTab(O,P)N:SelectTab(1)end m.AddSignal(v.TabHolder:GetPropertyChangedSignal'CanvasPosition',function()I=N:GetCurrentTabPos()+16 J=0 v.SelectorPosMotor:setGoal(r(N:GetCurrentTabPos()))end)return v end end,[18]=function()local c,d,e,f,g=b(18)local h=d.Parent local i,j,k=e(h.Themes),e(h.Packages.Flipper),{Registry={},Signals={},TransparencyMotors={},DefaultProperties={ScreenGui={ResetOnSpawn=false,ZIndexBehavior=Enum.ZIndexBehavior.Sibling},Frame={BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),BorderSizePixel=0},ScrollingFrame={BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),ScrollBarImageColor3=Color3.new(0,0,0)},TextLabel={BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),Font=Enum.Font.SourceSans,Text='',TextColor3=Color3.new(0,0,0),BackgroundTransparency=1,TextSize=14},TextButton={BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),AutoButtonColor=false,Font=Enum.Font.SourceSans,Text='',TextColor3=Color3.new(0,0,0),TextSize=14},TextBox={BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),ClearTextOnFocus=false,Font=Enum.Font.SourceSans,Text='',TextColor3=Color3.new(0,0,0),TextSize=14},ImageLabel={BackgroundTransparency=1,BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),BorderSizePixel=0},ImageButton={BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),AutoButtonColor=false},CanvasGroup={BackgroundColor3=Color3.new(1,1,1),BorderColor3=Color3.new(0,0,0),BorderSizePixel=0}}}local l=function(l,m)if m.ThemeTag then k.AddThemeObject(l,m.ThemeTag)end end function k.AddSignal(m,n)table.insert(k.Signals,m:Connect(n))end function k.Disconnect()for m=#k.Signals,1,-1 do local n=table.remove(k.Signals,m)n:Disconnect()end end function k.GetThemeProperty(m)if i[e(h).Theme][m]then return i[e(h).Theme][m]end return i.Dark[m]end function k.UpdateTheme()for m,n in next,k.Registry do for o,p in next,n.Properties do m[o]=k.GetThemeProperty(p)end end for o,p in next,k.TransparencyMotors do p:setGoal(j.Instant.new(k.GetThemeProperty'ElementTransparency'))end end function k.AddThemeObject(m,n)local o=#k.Registry+1 local p={Object=m,Properties=n,Idx=o}k.Registry[m]=p k.UpdateTheme()return m end function k.OverrideTag(m,n)k.Registry[m].Properties=n k.UpdateTheme()end function k.New(m,n,o)local p=Instance.new(m)for q,r in next,k.DefaultProperties[m]or{}do p[q]=r end for s,t in next,n or{}do if s~='ThemeTag'then p[s]=t end end for u,v in next,o or{}do v.Parent=p end l(p,n)return p end function k.SpringMotor(m,n,o,p,s)p=p or false s=s or false local t=j.SingleMotor.new(m)t:onStep(function(u)n[o]=u end)if s then table.insert(k.TransparencyMotors,t)end local u=function(u,v)v=v or false if not p then if not v then if o=='BackgroundTransparency'and e(h).DialogOpen then return end end end t:setGoal(j.Spring.new(u,{frequency=8}))end return t,u end return k end,[19]=function()local c,d,e,f,g=b(19)local h={}for i,j in next,d:GetChildren()do table.insert(h,e(j))end return h end,[20]=function()local c,d,e,f,g=b(20)local h=d.Parent.Parent local i=e(h.Creator)local j,k,l=i.New,h.Components,{}l.__index=l l.__type='Button'function l.New(m,n)assert(n.Title,'Button - Missing Title')n.Callback=n.Callback or function()end local o=e(k.Element)(n.Title,n.Description,m.Container,true)local p=j('ImageLabel',{Image='rbxassetid://10709791437',Size=UDim2.fromOffset(16,16),AnchorPoint=Vector2.new(1,0.5),Position=UDim2.new(1,-10,0.5,0),BackgroundTransparency=1,Parent=o.Frame,ThemeTag={ImageColor3='Text'}})i.AddSignal(o.Frame.MouseButton1Click,function()m.Library:SafeCallback(n.Callback)end)return o end return l end,[21]=function()local c,d,e,f,g=b(21)local h,i,j,k=game:GetService'UserInputService',game:GetService'TouchInputService',game:GetService'RunService',game:GetService'Players'local l,m=j.RenderStepped,k.LocalPlayer local n,o=m:GetMouse(),d.Parent.Parent local p=e(o.Creator)local s,t,u=p.New,o.Components,{}u.__index=u u.__type='Colorpicker'function u.New(v,w,x)local y=v.Library assert(x.Title,'Colorpicker - Missing Title')assert(x.Default,'AddColorPicker: Missing default value.')local z={Value=x.Default,Transparency=x.Transparency or 0,Type='Colorpicker',Title=type(x.Title)=='string'and x.Title or'Colorpicker',Callback=x.Callback or function(z)end}function z.SetHSVFromRGB(A,B)local C,D,E=Color3.toHSV(B)z.Hue=C z.Sat=D z.Vib=E end z:SetHSVFromRGB(z.Value)local A=e(t.Element)(x.Title,x.Description,v.Container,true)z.SetTitle=A.SetTitle z.SetDesc=A.SetDesc local B=s('Frame',{Size=UDim2.fromScale(1,1),BackgroundColor3=z.Value,Parent=A.Frame},{s('UICorner',{CornerRadius=UDim.new(0,4)})})local aa,ab=s('ImageLabel',{Size=UDim2.fromOffset(26,26),Position=UDim2.new(1,-10,0.5,0),AnchorPoint=Vector2.new(1,0.5),Parent=A.Frame,Image='http://www.roblox.com/asset/?id=14204231522',ImageTransparency=0.45,ScaleType=Enum.ScaleType.Tile,TileSize=UDim2.fromOffset(40,40)},{s('UICorner',{CornerRadius=UDim.new(0,4)}),B}),function()local C=e(t.Dialog):Create()C.Title.Text=z.Title C.Root.Size=UDim2.fromOffset(430,330)local D,E,F,G,H,I=z.Hue,z.Sat,z.Vib,z.Transparency,function()local D=e(t.Textbox)()D.Frame.Parent=C.Root D.Frame.Size=UDim2.new(0,90,0,32)return D end,function(D,E)return s('TextLabel',{FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.Medium,Enum.FontStyle.Normal),Text=D,TextColor3=Color3.fromRGB(240,240,240),TextSize=13,TextXAlignment=Enum.TextXAlignment.Left,Size=UDim2.new(1,0,0,32),Position=E,BackgroundTransparency=1,Parent=C.Root,ThemeTag={TextColor3='Text'}})end local J,K=function()local J=Color3.fromHSV(D,E,F)return{R=math.floor(J.r*255),G=math.floor(J.g*255),B=math.floor(J.b*255)}end,s('ImageLabel',{Size=UDim2.new(0,18,0,18),ScaleType=Enum.ScaleType.Fit,AnchorPoint=Vector2.new(0.5,0.5),BackgroundTransparency=1,Image='http://www.roblox.com/asset/?id=4805639000'})local L,M=s('ImageLabel',{Size=UDim2.fromOffset(180,160),Position=UDim2.fromOffset(20,55),Image='rbxassetid://4155801252',BackgroundColor3=z.Value,BackgroundTransparency=0,Parent=C.Root},{s('UICorner',{CornerRadius=UDim.new(0,4)}),K}),s('Frame',{BackgroundColor3=z.Value,Size=UDim2.fromScale(1,1),BackgroundTransparency=z.Transparency},{s('UICorner',{CornerRadius=UDim.new(0,4)})})local N,O=s('ImageLabel',{Image='http://www.roblox.com/asset/?id=14204231522',ImageTransparency=0.45,ScaleType=Enum.ScaleType.Tile,TileSize=UDim2.fromOffset(40,40),BackgroundTransparency=1,Position=UDim2.fromOffset(112,220),Size=UDim2.fromOffset(88,24),Parent=C.Root},{s('UICorner',{CornerRadius=UDim.new(0,4)}),s('UIStroke',{Thickness=2,Transparency=0.75}),M}),s('Frame',{BackgroundColor3=z.Value,Size=UDim2.fromScale(1,1),BackgroundTransparency=0},{s('UICorner',{CornerRadius=UDim.new(0,4)})})local P,Q=s('ImageLabel',{Image='http://www.roblox.com/asset/?id=14204231522',ImageTransparency=0.45,ScaleType=Enum.ScaleType.Tile,TileSize=UDim2.fromOffset(40,40),BackgroundTransparency=1,Position=UDim2.fromOffset(20,220),Size=UDim2.fromOffset(88,24),Parent=C.Root},{s('UICorner',{CornerRadius=UDim.new(0,4)}),s('UIStroke',{Thickness=2,Transparency=0.75}),O}),{}for R=0,1,0.1 do table.insert(Q,ColorSequenceKeypoint.new(R,Color3.fromHSV(R,1,1)))end local R,S=s('UIGradient',{Color=ColorSequence.new(Q),Rotation=90}),s('Frame',{Size=UDim2.new(1,0,1,-10),Position=UDim2.fromOffset(0,5),BackgroundTransparency=1})local T,U,V=s('ImageLabel',{Size=UDim2.fromOffset(14,14),Image='http://www.roblox.com/asset/?id=12266946128',Parent=S,ThemeTag={ImageColor3='DialogInput'}}),s('Frame',{Size=UDim2.fromOffset(12,190),Position=UDim2.fromOffset(210,55),Parent=C.Root},{s('UICorner',{CornerRadius=UDim.new(1,0)}),R,S}),H()V.Frame.Position=UDim2.fromOffset(x.Transparency and 260 or 240,55)I('Hex',UDim2.fromOffset(x.Transparency and 360 or 340,55))local W=H()W.Frame.Position=UDim2.fromOffset(x.Transparency and 260 or 240,95)I('Red',UDim2.fromOffset(x.Transparency and 360 or 340,95))local X=H()X.Frame.Position=UDim2.fromOffset(x.Transparency and 260 or 240,135)I('Green',UDim2.fromOffset(x.Transparency and 360 or 340,135))local Y=H()Y.Frame.Position=UDim2.fromOffset(x.Transparency and 260 or 240,175)I('Blue',UDim2.fromOffset(x.Transparency and 360 or 340,175))local Z if x.Transparency then Z=H()Z.Frame.Position=UDim2.fromOffset(260,215)I('Alpha',UDim2.fromOffset(360,215))end local _,aa,ab if x.Transparency then local ac=s('Frame',{Size=UDim2.new(1,0,1,-10),Position=UDim2.fromOffset(0,5),BackgroundTransparency=1})aa=s('ImageLabel',{Size=UDim2.fromOffset(14,14),Image='http://www.roblox.com/asset/?id=12266946128',Parent=ac,ThemeTag={ImageColor3='DialogInput'}})ab=s('Frame',{Size=UDim2.fromScale(1,1)},{s('UIGradient',{Transparency=NumberSequence.new{NumberSequenceKeypoint.new(0,0),NumberSequenceKeypoint.new(1,1)},Rotation=270}),s('UICorner',{CornerRadius=UDim.new(1,0)})})_=s('Frame',{Size=UDim2.fromOffset(12,190),Position=UDim2.fromOffset(230,55),Parent=C.Root,BackgroundTransparency=1},{s('UICorner',{CornerRadius=UDim.new(1,0)}),s('ImageLabel',{Image='http://www.roblox.com/asset/?id=14204231522',ImageTransparency=0.45,ScaleType=Enum.ScaleType.Tile,TileSize=UDim2.fromOffset(40,40),BackgroundTransparency=1,Size=UDim2.fromScale(1,1),Parent=C.Root},{s('UICorner',{CornerRadius=UDim.new(1,0)})}),ab,ac})end local ac=function()L.BackgroundColor3=Color3.fromHSV(D,1,1)T.Position=UDim2.new(0,-1,D,-6)K.Position=UDim2.new(E,0,1-F,0)O.BackgroundColor3=Color3.fromHSV(D,E,F)V.Input.Text='#'..Color3.fromHSV(D,E,F):ToHex()W.Input.Text=J().R X.Input.Text=J().G Y.Input.Text=J().B if x.Transparency then ab.BackgroundColor3=Color3.fromHSV(D,E,F)O.BackgroundTransparency=G aa.Position=UDim2.new(0,-1,1-G,-6)Z.Input.Text=e(o):Round((1-G)*100,0)..'%'end end p.AddSignal(V.Input.FocusLost,function(ad)if ad then local ae,af=pcall(Color3.fromHex,V.Input.Text)if ae and typeof(af)=='Color3'then D,E,F=Color3.toHSV(af)end end ac()end)p.AddSignal(W.Input.FocusLost,function(ad)if ad then local ae=J()local af,ag=pcall(Color3.fromRGB,W.Input.Text,ae.G,ae.B)if af and typeof(ag)=='Color3'then if tonumber(W.Input.Text)<=255 then D,E,F=Color3.toHSV(ag)end end end ac()end)p.AddSignal(X.Input.FocusLost,function(ad)if ad then local ae=J()local af,ag=pcall(Color3.fromRGB,ae.R,X.Input.Text,ae.B)if af and typeof(ag)=='Color3'then if tonumber(X.Input.Text)<=255 then D,E,F=Color3.toHSV(ag)end end end ac()end)p.AddSignal(Y.Input.FocusLost,function(ad)if ad then local ae=J()local af,ag=pcall(Color3.fromRGB,ae.R,ae.G,Y.Input.Text)if af and typeof(ag)=='Color3'then if tonumber(Y.Input.Text)<=255 then D,E,F=Color3.toHSV(ag)end end end ac()end)if x.Transparency then p.AddSignal(Z.Input.FocusLost,function(ad)if ad then pcall(function()local ae=tonumber(Z.Input.Text)if ae>=0 and ae<=100 then G=1-ae*0.01 end end)end ac()end)end p.AddSignal(L.InputBegan,function(ad)if ad.UserInputType==Enum.UserInputType.MouseButton1 or ad.UserInputType==Enum.UserInputType.Touch then while h:IsMouseButtonPressed(Enum.UserInputType.MouseButton1)do local ae=L.AbsolutePosition.X local af=ae+L.AbsoluteSize.X local ag,ah=math.clamp(n.X,ae,af),L.AbsolutePosition.Y local ai=ah+L.AbsoluteSize.Y local aj=math.clamp(n.Y,ah,ai)E=(ag-ae)/(af-ae)F=1-((aj-ah)/(ai-ah))ac()l:Wait()end end end)p.AddSignal(U.InputBegan,function(ad)if ad.UserInputType==Enum.UserInputType.MouseButton1 or ad.UserInputType==Enum.UserInputType.Touch then while h:IsMouseButtonPressed(Enum.UserInputType.MouseButton1)do local ae=U.AbsolutePosition.Y local af=ae+U.AbsoluteSize.Y local ag=math.clamp(n.Y,ae,af)D=((ag-ae)/(af-ae))ac()l:Wait()end end end)if x.Transparency then p.AddSignal(_.InputBegan,function(ad)if ad.UserInputType==Enum.UserInputType.MouseButton1 then while h:IsMouseButtonPressed(Enum.UserInputType.MouseButton1)do local ae=_.AbsolutePosition.Y local af=ae+_.AbsoluteSize.Y local ag=math.clamp(n.Y,ae,af)G=1-((ag-ae)/(af-ae))ac()l:Wait()end end end)end ac()C:Button('Done',function()z:SetValue({D,E,F},G)end)C:Button'Cancel'C:Open()end function z.Display(ac)z.Value=Color3.fromHSV(z.Hue,z.Sat,z.Vib)B.BackgroundColor3=z.Value B.BackgroundTransparency=z.Transparency u.Library:SafeCallback(z.Callback,z.Value)u.Library:SafeCallback(z.Changed,z.Value)end function z.SetValue(ac,ad,ae)local af=Color3.fromHSV(ad[1],ad[2],ad[3])z.Transparency=ae or 0 z:SetHSVFromRGB(af)z:Display()end function z.SetValueRGB(ac,ad,ae)z.Transparency=ae or 0 z:SetHSVFromRGB(ad)z:Display()end function z.OnChanged(ac,ad)z.Changed=ad ad(z.Value)end function z.Destroy(ac)A:Destroy()y.Options[w]=nil end p.AddSignal(A.Frame.MouseButton1Click,function()ab()end)z:Display()y.Options[w]=z return z end return u end,[22]=function()local aa,ab,ac,ad,ae=b(22)local af,ag,ah,ai,aj=game:GetService'TweenService',game:GetService'UserInputService',game:GetService'Players'.LocalPlayer:GetMouse(),game:GetService'Workspace'.CurrentCamera,ab.Parent.Parent local c,d=ac(aj.Creator),ac(aj.Packages.Flipper)local e,f,g=c.New,aj.Components,{}g.__index=g g.__type='Dropdown'function g.New(h,i,j)local k,l,m=h.Library,{Values=j.Values,Value=j.Default,Multi=j.Multi,Buttons={},Opened=false,Type='Dropdown',Callback=j.Callback or function()end},ac(f.Element)(j.Title,j.Description,h.Container,false)m.DescLabel.Size=UDim2.new(1,-170,0,14)l.SetTitle=m.SetTitle l.SetDesc=m.SetDesc local n,o=e('TextLabel',{FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.Regular,Enum.FontStyle.Normal),Text='Value',TextColor3=Color3.fromRGB(240,240,240),TextSize=13,TextXAlignment=Enum.TextXAlignment.Left,Size=UDim2.new(1,-30,0,14),Position=UDim2.new(0,8,0.5,0),AnchorPoint=Vector2.new(0,0.5),BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,TextTruncate=Enum.TextTruncate.AtEnd,ThemeTag={TextColor3='Text'}}),e('ImageLabel',{Image='rbxassetid://10709790948',Size=UDim2.fromOffset(16,16),AnchorPoint=Vector2.new(1,0.5),Position=UDim2.new(1,-8,0.5,0),BackgroundTransparency=1,ThemeTag={ImageColor3='SubText'}})local p,s=e('TextButton',{Size=UDim2.fromOffset(160,30),Position=UDim2.new(1,-10,0.5,0),AnchorPoint=Vector2.new(1,0.5),BackgroundTransparency=0.9,Parent=m.Frame,ThemeTag={BackgroundColor3='DropdownFrame'}},{e('UICorner',{CornerRadius=UDim.new(0,5)}),e('UIStroke',{Transparency=0.5,ApplyStrokeMode=Enum.ApplyStrokeMode.Border,ThemeTag={Color='InElementBorder'}}),o,n}),e('UIListLayout',{Padding=UDim.new(0,3)})local t=e('ScrollingFrame',{Size=UDim2.new(1,-5,1,-10),Position=UDim2.fromOffset(5,5),BackgroundTransparency=1,BottomImage='rbxassetid://6889812791',MidImage='rbxassetid://6889812721',TopImage='rbxassetid://6276641225',ScrollBarImageColor3=Color3.fromRGB(255,255,255),ScrollBarImageTransparency=0.95,ScrollBarThickness=4,BorderSizePixel=0,CanvasSize=UDim2.fromScale(0,0)},{s})local u=e('Frame',{Size=UDim2.fromScale(1,0.6),ThemeTag={BackgroundColor3='DropdownHolder'}},{t,e('UICorner',{CornerRadius=UDim.new(0,7)}),e('UIStroke',{ApplyStrokeMode=Enum.ApplyStrokeMode.Border,ThemeTag={Color='DropdownBorder'}}),e('ImageLabel',{BackgroundTransparency=1,Image='http://www.roblox.com/asset/?id=5554236805',ScaleType=Enum.ScaleType.Slice,SliceCenter=Rect.new(23,23,277,277),Size=UDim2.fromScale(1,1)+UDim2.fromOffset(30,30),Position=UDim2.fromOffset(-15,-15),ImageColor3=Color3.fromRGB(0,0,0),ImageTransparency=0.1})})local v=e('Frame',{BackgroundTransparency=1,Size=UDim2.fromOffset(170,300),Parent=h.Library.GUI,Visible=false},{u,e('UISizeConstraint',{MinSize=Vector2.new(170,0)})})table.insert(k.OpenFrames,v)local w,x=function()local w=0 if ai.ViewportSize.Y-p.AbsolutePosition.Y<v.AbsoluteSize.Y-5 then w=v.AbsoluteSize.Y-5-(ai.ViewportSize.Y-p.AbsolutePosition.Y)+40 end v.Position=UDim2.fromOffset(p.AbsolutePosition.X-1,p.AbsolutePosition.Y-5-w)end,0 local y,z=function()if#l.Values>10 then v.Size=UDim2.fromOffset(x,392)else v.Size=UDim2.fromOffset(x,s.AbsoluteContentSize.Y+10)end end,function()t.CanvasSize=UDim2.fromOffset(0,s.AbsoluteContentSize.Y)end w()y()c.AddSignal(p:GetPropertyChangedSignal'AbsolutePosition',w)c.AddSignal(p.MouseButton1Click,function()l:Open()end)c.AddSignal(ag.InputBegan,function(A)if A.UserInputType==Enum.UserInputType.MouseButton1 or A.UserInputType==Enum.UserInputType.Touch then local B,C=u.AbsolutePosition,u.AbsoluteSize if ah.X<B.X or ah.X>B.X+C.X or ah.Y<(B.Y-20-1)or ah.Y>B.Y+C.Y then l:Close()end end end)local A=h.ScrollFrame function l.Open(B)l.Opened=true A.ScrollingEnabled=false v.Visible=true af:Create(u,TweenInfo.new(0.2,Enum.EasingStyle.Quart,Enum.EasingDirection.Out),{Size=UDim2.fromScale(1,1)}):Play()end function l.Close(B)l.Opened=false A.ScrollingEnabled=true u.Size=UDim2.fromScale(1,0.6)v.Visible=false end function l.Display(B)local C,D=l.Values,''if j.Multi then for E,F in next,C do if l.Value[F]then D=D..F..', 'end end D=D:sub(1,#D-2)else D=l.Value or''end n.Text=(D==''and'--'or D)end function l.GetActiveValues(B)if j.Multi then local C={}for D,E in next,l.Value do table.insert(C,D)end return C else return l.Value and 1 or 0 end end function l.BuildDropdownList(B)local C,D=l.Values,{}for E,F in next,t:GetChildren()do if not F:IsA'UIListLayout'then F:Destroy()end end local G=0 for H,I in next,C do local J={}G=G+1 local K,L=e('Frame',{Size=UDim2.fromOffset(4,14),BackgroundColor3=Color3.fromRGB(76,194,255),Position=UDim2.fromOffset(-1,16),AnchorPoint=Vector2.new(0,0.5),ThemeTag={BackgroundColor3='Accent'}},{e('UICorner',{CornerRadius=UDim.new(0,2)})}),e('TextLabel',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',Text=I,TextColor3=Color3.fromRGB(200,200,200),TextSize=13,TextXAlignment=Enum.TextXAlignment.Left,BackgroundColor3=Color3.fromRGB(255,255,255),AutomaticSize=Enum.AutomaticSize.Y,BackgroundTransparency=1,Size=UDim2.fromScale(1,1),Position=UDim2.fromOffset(10,0),Name='ButtonLabel',ThemeTag={TextColor3='Text'}})local M,N=(e('TextButton',{Size=UDim2.new(1,-5,0,32),BackgroundTransparency=1,ZIndex=23,Text='',Parent=t,ThemeTag={BackgroundColor3='DropdownOption'}},{K,L,e('UICorner',{CornerRadius=UDim.new(0,6)})}))if j.Multi then N=l.Value[I]else N=l.Value==I end local O,P=c.SpringMotor(1,M,'BackgroundTransparency')local Q,R=c.SpringMotor(1,K,'BackgroundTransparency')local S=d.SingleMotor.new(6)S:onStep(function(T)K.Size=UDim2.new(0,4,0,T)end)c.AddSignal(M.MouseEnter,function()P(N and 0.85 or 0.89)end)c.AddSignal(M.MouseLeave,function()P(N and 0.89 or 1)end)c.AddSignal(M.MouseButton1Down,function()P(0.92)end)c.AddSignal(M.MouseButton1Up,function()P(N and 0.85 or 0.89)end)function J.UpdateButton(T)if j.Multi then N=l.Value[I]if N then P(0.89)end else N=l.Value==I P(N and 0.89 or 1)end S:setGoal(d.Spring.new(N and 14 or 6,{frequency=6}))R(N and 0 or 1)end L.InputBegan:Connect(function(T)if T.UserInputType==Enum.UserInputType.MouseButton1 or T.UserInputType==Enum.UserInputType.Touch then local U=not N if l:GetActiveValues()==1 and not U and not j.AllowNull then else if j.Multi then N=U l.Value[I]=N and true or nil else N=U l.Value=N and I or nil for V,W in next,D do W:UpdateButton()end end J:UpdateButton()l:Display()k:SafeCallback(l.Callback,l.Value)k:SafeCallback(l.Changed,l.Value)end end end)J:UpdateButton()l:Display()D[M]=J end x=0 for J,K in next,D do if J.ButtonLabel then if J.ButtonLabel.TextBounds.X>x then x=J.ButtonLabel.TextBounds.X end end end x=x+30 z()y()end function l.SetValues(B,C)if C then l.Values=C end l:BuildDropdownList()end function l.OnChanged(B,C)l.Changed=C C(l.Value)end function l.SetValue(B,C)if l.Multi then local D={}for E,F in next,C do if table.find(l.Values,E)then D[E]=true end end l.Value=D else if not C then l.Value=nil elseif table.find(l.Values,C)then l.Value=C end end l:BuildDropdownList()k:SafeCallback(l.Callback,l.Value)k:SafeCallback(l.Changed,l.Value)end function l.Destroy(B)m:Destroy()k.Options[i]=nil end l:BuildDropdownList()l:Display()local B={}if type(j.Default)=='string'then local C=table.find(l.Values,j.Default)if C then table.insert(B,C)end elseif type(j.Default)=='table'then for C,D in next,j.Default do local E=table.find(l.Values,D)if E then table.insert(B,E)end end elseif type(j.Default)=='number'and l.Values[j.Default]~=nil then table.insert(B,j.Default)end if next(B)then for C=1,#B do local D=B[C]if j.Multi then l.Value[l.Values[D]]=true else l.Value=l.Values[D]end if not j.Multi then break end end l:BuildDropdownList()l:Display()end k.Options[i]=l return l end return g end,[23]=function()local aa,ab,ac,ad,ae=b(23)local af=ab.Parent.Parent local ag=ac(af.Creator)local ah,ai,aj,c=ag.New,ag.AddSignal,af.Components,{}c.__index=c c.__type='Input'function c.New(d,e,f)local g=d.Library assert(f.Title,'Input - Missing Title')f.Callback=f.Callback or function()end local h,i={Value=f.Default or'',Numeric=f.Numeric or false,Finished=f.Finished or false,Callback=f.Callback or function(h)end,Type='Input'},ac(aj.Element)(f.Title,f.Description,d.Container,false)h.SetTitle=i.SetTitle h.SetDesc=i.SetDesc local j=ac(aj.Textbox)(i.Frame,true)j.Frame.Position=UDim2.new(1,-10,0.5,0)j.Frame.AnchorPoint=Vector2.new(1,0.5)j.Frame.Size=UDim2.fromOffset(160,30)j.Input.Text=f.Default or''j.Input.PlaceholderText=f.Placeholder or''local k=j.Input function h.SetValue(l,m)if f.MaxLength and#m>f.MaxLength then m=m:sub(1,f.MaxLength)end if h.Numeric then if(not tonumber(m))and m:len()>0 then m=h.Value end end h.Value=m k.Text=m g:SafeCallback(h.Callback,h.Value)g:SafeCallback(h.Changed,h.Value)end if h.Finished then ai(k.FocusLost,function(l)if not l then return end h:SetValue(k.Text)end)else ai(k:GetPropertyChangedSignal'Text',function()h:SetValue(k.Text)end)end function h.OnChanged(l,m)h.Changed=m m(h.Value)end function h.Destroy(l)i:Destroy()g.Options[e]=nil end g.Options[e]=h return h end return c end,[24]=function()local aa,ab,ac,ad,ae=b(24)local af,ag=game:GetService'UserInputService',ab.Parent.Parent local ah=ac(ag.Creator)local ai,aj,c=ah.New,ag.Components,{}c.__index=c c.__type='Keybind'function c.New(d,e,f)local g=d.Library assert(f.Title,'KeyBind - Missing Title')assert(f.Default,'KeyBind - Missing default value.')local h,i,j={Value=f.Default,Toggled=false,Mode=f.Mode or'Toggle',Type='Keybind',Callback=f.Callback or function(h)end,ChangedCallback=f.ChangedCallback or function(h)end},false,ac(aj.Element)(f.Title,f.Description,d.Container,true)h.SetTitle=j.SetTitle h.SetDesc=j.SetDesc local k=ai('TextLabel',{FontFace=Font.new('rbxasset://fonts/families/GothamSSm.json',Enum.FontWeight.Regular,Enum.FontStyle.Normal),Text=f.Default,TextColor3=Color3.fromRGB(240,240,240),TextSize=13,TextXAlignment=Enum.TextXAlignment.Center,Size=UDim2.new(0,0,0,14),Position=UDim2.new(0,0,0.5,0),AnchorPoint=Vector2.new(0,0.5),BackgroundColor3=Color3.fromRGB(255,255,255),AutomaticSize=Enum.AutomaticSize.X,BackgroundTransparency=1,ThemeTag={TextColor3='Text'}})local l=ai('TextButton',{Size=UDim2.fromOffset(0,30),Position=UDim2.new(1,-10,0.5,0),AnchorPoint=Vector2.new(1,0.5),BackgroundTransparency=0.9,Parent=j.Frame,AutomaticSize=Enum.AutomaticSize.X,ThemeTag={BackgroundColor3='Keybind'}},{ai('UICorner',{CornerRadius=UDim.new(0,5)}),ai('UIPadding',{PaddingLeft=UDim.new(0,8),PaddingRight=UDim.new(0,8)}),ai('UIStroke',{Transparency=0.5,ApplyStrokeMode=Enum.ApplyStrokeMode.Border,ThemeTag={Color='InElementBorder'}}),k})function h.GetState(m)if af:GetFocusedTextBox()and h.Mode~='Always'then return false end if h.Mode=='Always'then return true elseif h.Mode=='Hold'then if h.Value=='None'then return false end local n=h.Value if n=='MouseLeft'or n=='MouseRight'then return n=='MouseLeft'and af:IsMouseButtonPressed(Enum.UserInputType.MouseButton1)or n=='MouseRight'and af:IsMouseButtonPressed(Enum.UserInputType.MouseButton2)else return af:IsKeyDown(Enum.KeyCode[h.Value])end else return h.Toggled end end function h.SetValue(m,n,o)n=n or h.Key o=o or h.Mode k.Text=n h.Value=n h.Mode=o end function h.OnClick(m,n)h.Clicked=n end function h.OnChanged(m,n)h.Changed=n n(h.Value)end function h.DoClick(m)g:SafeCallback(h.Callback,h.Toggled)g:SafeCallback(h.Clicked,h.Toggled)end function h.Destroy(m)j:Destroy()g.Options[e]=nil end ah.AddSignal(l.InputBegan,function(m)if m.UserInputType==Enum.UserInputType.MouseButton1 or m.UserInputType==Enum.UserInputType.Touch then i=true k.Text='...'wait(0.2)local n n=af.InputBegan:Connect(function(o)local p if o.UserInputType==Enum.UserInputType.Keyboard then p=o.KeyCode.Name elseif o.UserInputType==Enum.UserInputType.MouseButton1 then p='MouseLeft'elseif o.UserInputType==Enum.UserInputType.MouseButton2 then p='MouseRight'end local s s=af.InputEnded:Connect(function(t)if t.KeyCode.Name==p or p=='MouseLeft'and t.UserInputType==Enum.UserInputType.MouseButton1 or p=='MouseRight'and t.UserInputType==Enum.UserInputType.MouseButton2 then i=false k.Text=p h.Value=p g:SafeCallback(h.ChangedCallback,t.KeyCode or t.UserInputType)g:SafeCallback(h.Changed,t.KeyCode or t.UserInputType)n:Disconnect()s:Disconnect()end end)end)end end)ah.AddSignal(af.InputBegan,function(m)if not i and not af:GetFocusedTextBox()then if h.Mode=='Toggle'then local n=h.Value if n=='MouseLeft'or n=='MouseRight'then if n=='MouseLeft'and m.UserInputType==Enum.UserInputType.MouseButton1 or n=='MouseRight'and m.UserInputType==Enum.UserInputType.MouseButton2 then h.Toggled=not h.Toggled h:DoClick()end elseif m.UserInputType==Enum.UserInputType.Keyboard then if m.KeyCode.Name==n then h.Toggled=not h.Toggled h:DoClick()end end end end end)g.Options[e]=h return h end return c end,[25]=function()local aa,ab,ac,ad,ae=b(25)local af=ab.Parent.Parent local ag,ah,ai,aj=af.Components,ac(af.Packages.Flipper),ac(af.Creator),{}aj.__index=aj aj.__type='Paragraph'function aj.New(c,d)assert(d.Title,'Paragraph - Missing Title')d.Content=d.Content or''local e=ac(ag.Element)(d.Title,d.Content,aj.Container,false)e.Frame.BackgroundTransparency=0.92 e.Border.Transparency=0.6 return e end return aj end,[26]=function()local aa,ab,ac,ad,ae=b(26)local af,ag=game:GetService'UserInputService',ab.Parent.Parent local ah=ac(ag.Creator)local ai,aj,c=ah.New,ag.Components,{}c.__index=c c.__type='Slider'function c.New(d,e,f)local g=d.Library assert(f.Title,'Slider - Missing Title.')assert(f.Default,'Slider - Missing default value.')assert(f.Min,'Slider - Missing minimum value.')assert(f.Max,'Slider - Missing maximum value.')assert(f.Rounding,'Slider - Missing rounding value.')local h,i,j={Value=nil,Min=f.Min,Max=f.Max,Rounding=f.Rounding,Callback=f.Callback or function(h)end,Type='Slider'},false,ac(aj.Element)(f.Title,f.Description,d.Container,false)j.DescLabel.Size=UDim2.new(1,-170,0,14)h.SetTitle=j.SetTitle h.SetDesc=j.SetDesc local k=ai('ImageLabel',{AnchorPoint=Vector2.new(0,0.5),Position=UDim2.new(0,-7,0.5,0),Size=UDim2.fromOffset(14,14),Image='http://www.roblox.com/asset/?id=12266946128',ThemeTag={ImageColor3='Accent'}})local l,m,n=ai('Frame',{BackgroundTransparency=1,Position=UDim2.fromOffset(7,0),Size=UDim2.new(1,-14,1,0)},{k}),ai('Frame',{Size=UDim2.new(0,0,1,0),ThemeTag={BackgroundColor3='Accent'}},{ai('UICorner',{CornerRadius=UDim.new(1,0)})}),ai('TextLabel',{FontFace=Font.new'rbxasset://fonts/families/GothamSSm.json',Text='Value',TextSize=12,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Right,BackgroundColor3=Color3.fromRGB(255,255,255),BackgroundTransparency=1,Size=UDim2.new(0,100,0,14),Position=UDim2.new(0,-4,0.5,0),AnchorPoint=Vector2.new(1,0.5),ThemeTag={TextColor3='SubText'}})local o=ai('Frame',{Size=UDim2.new(1,0,0,4),AnchorPoint=Vector2.new(1,0.5),Position=UDim2.new(1,-10,0.5,0),BackgroundTransparency=0.4,Parent=j.Frame,ThemeTag={BackgroundColor3='SliderRail'}},{ai('UICorner',{CornerRadius=UDim.new(1,0)}),ai('UISizeConstraint',{MaxSize=Vector2.new(150,math.huge)}),n,m,l})ah.AddSignal(k.InputBegan,function(p)if p.UserInputType==Enum.UserInputType.MouseButton1 or p.UserInputType==Enum.UserInputType.Touch then i=true end end)ah.AddSignal(k.InputEnded,function(p)if p.UserInputType==Enum.UserInputType.MouseButton1 or p.UserInputType==Enum.UserInputType.Touch then i=false end end)ah.AddSignal(af.InputChanged,function(p)if i and(p.UserInputType==Enum.UserInputType.MouseMovement or p.UserInputType==Enum.UserInputType.Touch)then local s=math.clamp((p.Position.X-l.AbsolutePosition.X)/l.AbsoluteSize.X,0,1)h:SetValue(h.Min+((h.Max-h.Min)*s))end end)function h.OnChanged(p,s)h.Changed=s s(h.Value)end function h.SetValue(p,s)p.Value=g:Round(math.clamp(s,h.Min,h.Max),h.Rounding)k.Position=UDim2.new((p.Value-h.Min)/(h.Max-h.Min),-7,0.5,0)m.Size=UDim2.fromScale((p.Value-h.Min)/(h.Max-h.Min),1)n.Text=tostring(p.Value)g:SafeCallback(h.Callback,p.Value)g:SafeCallback(h.Changed,p.Value)end function h.Destroy(p)j:Destroy()g.Options[e]=nil end h:SetValue(f.Default)g.Options[e]=h return h end return c end,[27]=function()local aa,ab,ac,ad,ae=b(27)local af,ag=game:GetService'TweenService',ab.Parent.Parent local ah=ac(ag.Creator)local ai,aj,c=ah.New,ag.Components,{}c.__index=c c.__type='Toggle'function c.New(d,e,f)local g=d.Library assert(f.Title,'Toggle - Missing Title')local h,i={Value=f.Default or false,Callback=f.Callback or function(h)end,Type='Toggle'},ac(aj.Element)(f.Title,f.Description,d.Container,true)i.DescLabel.Size=UDim2.new(1,-54,0,14)h.SetTitle=i.SetTitle h.SetDesc=i.SetDesc local j,k=ai('ImageLabel',{AnchorPoint=Vector2.new(0,0.5),Size=UDim2.fromOffset(14,14),Position=UDim2.new(0,2,0.5,0),Image='http://www.roblox.com/asset/?id=12266946128',ImageTransparency=0.5,ThemeTag={ImageColor3='ToggleSlider'}}),ai('UIStroke',{Transparency=0.5,ThemeTag={Color='ToggleSlider'}})local l=ai('Frame',{Size=UDim2.fromOffset(36,18),AnchorPoint=Vector2.new(1,0.5),Position=UDim2.new(1,-10,0.5,0),Parent=i.Frame,BackgroundTransparency=1,ThemeTag={BackgroundColor3='Accent'}},{ai('UICorner',{CornerRadius=UDim.new(0,9)}),k,j})function h.OnChanged(m,n)h.Changed=n n(h.Value)end function h.SetValue(m,n)n=not not n h.Value=n ah.OverrideTag(k,{Color=h.Value and'Accent'or'ToggleSlider'})ah.OverrideTag(j,{ImageColor3=h.Value and'ToggleToggled'or'ToggleSlider'})af:Create(j,TweenInfo.new(0.25,Enum.EasingStyle.Quint,Enum.EasingDirection.Out),{Position=UDim2.new(0,h.Value and 19 or 2,0.5,0)}):Play()af:Create(l,TweenInfo.new(0.25,Enum.EasingStyle.Quint,Enum.EasingDirection.Out),{BackgroundTransparency=h.Value and 0 or 1}):Play()j.ImageTransparency=h.Value and 0 or 0.5 g:SafeCallback(h.Callback,h.Value)g:SafeCallback(h.Changed,h.Value)end function h.Destroy(m)i:Destroy()g.Options[e]=nil end ah.AddSignal(i.Frame.MouseButton1Click,function()h:SetValue(not h.Value)end)h:SetValue(h.Value)g.Options[e]=h return h end return c end,[28]=function()local aa,ab,ac,ad,ae=b(28)return{assets={['lucide-accessibility']='rbxassetid://10709751939',['lucide-activity']='rbxassetid://10709752035',['lucide-air-vent']='rbxassetid://10709752131',['lucide-airplay']='rbxassetid://10709752254',['lucide-alarm-check']='rbxassetid://10709752405',['lucide-alarm-clock']='rbxassetid://10709752630',['lucide-alarm-clock-off']='rbxassetid://10709752508',['lucide-alarm-minus']='rbxassetid://10709752732',['lucide-alarm-plus']='rbxassetid://10709752825',['lucide-album']='rbxassetid://10709752906',['lucide-alert-circle']='rbxassetid://10709752996',['lucide-alert-octagon']='rbxassetid://10709753064',['lucide-alert-triangle']='rbxassetid://10709753149',['lucide-align-center']='rbxassetid://10709753570',['lucide-align-center-horizontal']='rbxassetid://10709753272',['lucide-align-center-vertical']='rbxassetid://10709753421',['lucide-align-end-horizontal']='rbxassetid://10709753692',['lucide-align-end-vertical']='rbxassetid://10709753808',['lucide-align-horizontal-distribute-center']='rbxassetid://10747779791',['lucide-align-horizontal-distribute-end']='rbxassetid://10747784534',['lucide-align-horizontal-distribute-start']='rbxassetid://10709754118',['lucide-align-horizontal-justify-center']='rbxassetid://10709754204',['lucide-align-horizontal-justify-end']='rbxassetid://10709754317',['lucide-align-horizontal-justify-start']='rbxassetid://10709754436',['lucide-align-horizontal-space-around']='rbxassetid://10709754590',['lucide-align-horizontal-space-between']='rbxassetid://10709754749',['lucide-align-justify']='rbxassetid://10709759610',['lucide-align-left']='rbxassetid://10709759764',['lucide-align-right']='rbxassetid://10709759895',['lucide-align-start-horizontal']='rbxassetid://10709760051',['lucide-align-start-vertical']='rbxassetid://10709760244',['lucide-align-vertical-distribute-center']='rbxassetid://10709760351',['lucide-align-vertical-distribute-end']='rbxassetid://10709760434',['lucide-align-vertical-distribute-start']='rbxassetid://10709760612',['lucide-align-vertical-justify-center']='rbxassetid://10709760814',['lucide-align-vertical-justify-end']='rbxassetid://10709761003',['lucide-align-vertical-justify-start']='rbxassetid://10709761176',['lucide-align-vertical-space-around']='rbxassetid://10709761324',['lucide-align-vertical-space-between']='rbxassetid://10709761434',['lucide-anchor']='rbxassetid://10709761530',['lucide-angry']='rbxassetid://10709761629',['lucide-annoyed']='rbxassetid://10709761722',['lucide-aperture']='rbxassetid://10709761813',['lucide-apple']='rbxassetid://10709761889',['lucide-archive']='rbxassetid://10709762233',['lucide-archive-restore']='rbxassetid://10709762058',['lucide-armchair']='rbxassetid://10709762327',['lucide-arrow-big-down']='rbxassetid://10747796644',['lucide-arrow-big-left']='rbxassetid://10709762574',['lucide-arrow-big-right']='rbxassetid://10709762727',['lucide-arrow-big-up']='rbxassetid://10709762879',['lucide-arrow-down']='rbxassetid://10709767827',['lucide-arrow-down-circle']='rbxassetid://10709763034',['lucide-arrow-down-left']='rbxassetid://10709767656',['lucide-arrow-down-right']='rbxassetid://10709767750',['lucide-arrow-left']='rbxassetid://10709768114',['lucide-arrow-left-circle']='rbxassetid://10709767936',['lucide-arrow-left-right']='rbxassetid://10709768019',['lucide-arrow-right']='rbxassetid://10709768347',['lucide-arrow-right-circle']='rbxassetid://10709768226',['lucide-arrow-up']='rbxassetid://10709768939',['lucide-arrow-up-circle']='rbxassetid://10709768432',['lucide-arrow-up-down']='rbxassetid://10709768538',['lucide-arrow-up-left']='rbxassetid://10709768661',['lucide-arrow-up-right']='rbxassetid://10709768787',['lucide-asterisk']='rbxassetid://10709769095',['lucide-at-sign']='rbxassetid://10709769286',['lucide-award']='rbxassetid://10709769406',['lucide-axe']='rbxassetid://10709769508',['lucide-axis-3d']='rbxassetid://10709769598',['lucide-baby']='rbxassetid://10709769732',['lucide-backpack']='rbxassetid://10709769841',['lucide-baggage-claim']='rbxassetid://10709769935',['lucide-banana']='rbxassetid://10709770005',['lucide-banknote']='rbxassetid://10709770178',['lucide-bar-chart']='rbxassetid://10709773755',['lucide-bar-chart-2']='rbxassetid://10709770317',['lucide-bar-chart-3']='rbxassetid://10709770431',['lucide-bar-chart-4']='rbxassetid://10709770560',['lucide-bar-chart-horizontal']='rbxassetid://10709773669',['lucide-barcode']='rbxassetid://10747360675',['lucide-baseline']='rbxassetid://10709773863',['lucide-bath']='rbxassetid://10709773963',['lucide-battery']='rbxassetid://10709774640',['lucide-battery-charging']='rbxassetid://10709774068',['lucide-battery-full']='rbxassetid://10709774206',['lucide-battery-low']='rbxassetid://10709774370',['lucide-battery-medium']='rbxassetid://10709774513',['lucide-beaker']='rbxassetid://10709774756',['lucide-bed']='rbxassetid://10709775036',['lucide-bed-double']='rbxassetid://10709774864',['lucide-bed-single']='rbxassetid://10709774968',['lucide-beer']='rbxassetid://10709775167',['lucide-bell']='rbxassetid://10709775704',['lucide-bell-minus']='rbxassetid://10709775241',['lucide-bell-off']='rbxassetid://10709775320',['lucide-bell-plus']='rbxassetid://10709775448',['lucide-bell-ring']='rbxassetid://10709775560',['lucide-bike']='rbxassetid://10709775894',['lucide-binary']='rbxassetid://10709776050',['lucide-bitcoin']='rbxassetid://10709776126',['lucide-bluetooth']='rbxassetid://10709776655',['lucide-bluetooth-connected']='rbxassetid://10709776240',['lucide-bluetooth-off']='rbxassetid://10709776344',['lucide-bluetooth-searching']='rbxassetid://10709776501',['lucide-bold']='rbxassetid://10747813908',['lucide-bomb']='rbxassetid://10709781460',['lucide-bone']='rbxassetid://10709781605',['lucide-book']='rbxassetid://10709781824',['lucide-book-open']='rbxassetid://10709781717',['lucide-bookmark']='rbxassetid://10709782154',['lucide-bookmark-minus']='rbxassetid://10709781919',['lucide-bookmark-plus']='rbxassetid://10709782044',['lucide-bot']='rbxassetid://10709782230',['lucide-box']='rbxassetid://10709782497',['lucide-box-select']='rbxassetid://10709782342',['lucide-boxes']='rbxassetid://10709782582',['lucide-briefcase']='rbxassetid://10709782662',['lucide-brush']='rbxassetid://10709782758',['lucide-bug']='rbxassetid://10709782845',['lucide-building']='rbxassetid://10709783051',['lucide-building-2']='rbxassetid://10709782939',['lucide-bus']='rbxassetid://10709783137',['lucide-cake']='rbxassetid://10709783217',['lucide-calculator']='rbxassetid://10709783311',['lucide-calendar']='rbxassetid://10709789505',['lucide-calendar-check']='rbxassetid://10709783474',['lucide-calendar-check-2']='rbxassetid://10709783392',['lucide-calendar-clock']='rbxassetid://10709783577',['lucide-calendar-days']='rbxassetid://10709783673',['lucide-calendar-heart']='rbxassetid://10709783835',['lucide-calendar-minus']='rbxassetid://10709783959',['lucide-calendar-off']='rbxassetid://10709788784',['lucide-calendar-plus']='rbxassetid://10709788937',['lucide-calendar-range']='rbxassetid://10709789053',['lucide-calendar-search']='rbxassetid://10709789200',['lucide-calendar-x']='rbxassetid://10709789407',['lucide-calendar-x-2']='rbxassetid://10709789329',['lucide-camera']='rbxassetid://10709789686',['lucide-camera-off']='rbxassetid://10747822677',['lucide-car']='rbxassetid://10709789810',['lucide-carrot']='rbxassetid://10709789960',['lucide-cast']='rbxassetid://10709790097',['lucide-charge']='rbxassetid://10709790202',['lucide-check']='rbxassetid://10709790644',['lucide-check-circle']='rbxassetid://10709790387',['lucide-check-circle-2']='rbxassetid://10709790298',['lucide-check-square']='rbxassetid://10709790537',['lucide-chef-hat']='rbxassetid://10709790757',['lucide-cherry']='rbxassetid://10709790875',['lucide-chevron-down']='rbxassetid://10709790948',['lucide-chevron-first']='rbxassetid://10709791015',['lucide-chevron-last']='rbxassetid://10709791130',['lucide-chevron-left']='rbxassetid://10709791281',['lucide-chevron-right']='rbxassetid://10709791437',['lucide-chevron-up']='rbxassetid://10709791523',['lucide-chevrons-down']='rbxassetid://10709796864',['lucide-chevrons-down-up']='rbxassetid://10709791632',['lucide-chevrons-left']='rbxassetid://10709797151',['lucide-chevrons-left-right']='rbxassetid://10709797006',['lucide-chevrons-right']='rbxassetid://10709797382',['lucide-chevrons-right-left']='rbxassetid://10709797274',['lucide-chevrons-up']='rbxassetid://10709797622',['lucide-chevrons-up-down']='rbxassetid://10709797508',['lucide-chrome']='rbxassetid://10709797725',['lucide-circle']='rbxassetid://10709798174',['lucide-circle-dot']='rbxassetid://10709797837',['lucide-circle-ellipsis']='rbxassetid://10709797985',['lucide-circle-slashed']='rbxassetid://10709798100',['lucide-citrus']='rbxassetid://10709798276',['lucide-clapperboard']='rbxassetid://10709798350',['lucide-clipboard']='rbxassetid://10709799288',['lucide-clipboard-check']='rbxassetid://10709798443',['lucide-clipboard-copy']='rbxassetid://10709798574',['lucide-clipboard-edit']='rbxassetid://10709798682',['lucide-clipboard-list']='rbxassetid://10709798792',['lucide-clipboard-signature']='rbxassetid://10709798890',['lucide-clipboard-type']='rbxassetid://10709798999',['lucide-clipboard-x']='rbxassetid://10709799124',['lucide-clock']='rbxassetid://10709805144',['lucide-clock-1']='rbxassetid://10709799535',['lucide-clock-10']='rbxassetid://10709799718',['lucide-clock-11']='rbxassetid://10709799818',['lucide-clock-12']='rbxassetid://10709799962',['lucide-clock-2']='rbxassetid://10709803876',['lucide-clock-3']='rbxassetid://10709803989',['lucide-clock-4']='rbxassetid://10709804164',['lucide-clock-5']='rbxassetid://10709804291',['lucide-clock-6']='rbxassetid://10709804435',['lucide-clock-7']='rbxassetid://10709804599',['lucide-clock-8']='rbxassetid://10709804784',['lucide-clock-9']='rbxassetid://10709804996',['lucide-cloud']='rbxassetid://10709806740',['lucide-cloud-cog']='rbxassetid://10709805262',['lucide-cloud-drizzle']='rbxassetid://10709805371',['lucide-cloud-fog']='rbxassetid://10709805477',['lucide-cloud-hail']='rbxassetid://10709805596',['lucide-cloud-lightning']='rbxassetid://10709805727',['lucide-cloud-moon']='rbxassetid://10709805942',['lucide-cloud-moon-rain']='rbxassetid://10709805838',['lucide-cloud-off']='rbxassetid://10709806060',['lucide-cloud-rain']='rbxassetid://10709806277',['lucide-cloud-rain-wind']='rbxassetid://10709806166',['lucide-cloud-snow']='rbxassetid://10709806374',['lucide-cloud-sun']='rbxassetid://10709806631',['lucide-cloud-sun-rain']='rbxassetid://10709806475',['lucide-cloudy']='rbxassetid://10709806859',['lucide-clover']='rbxassetid://10709806995',['lucide-code']='rbxassetid://10709810463',['lucide-code-2']='rbxassetid://10709807111',['lucide-codepen']='rbxassetid://10709810534',['lucide-codesandbox']='rbxassetid://10709810676',['lucide-coffee']='rbxassetid://10709810814',['lucide-cog']='rbxassetid://10709810948',['lucide-coins']='rbxassetid://10709811110',['lucide-columns']='rbxassetid://10709811261',['lucide-command']='rbxassetid://10709811365',['lucide-compass']='rbxassetid://10709811445',['lucide-component']='rbxassetid://10709811595',['lucide-concierge-bell']='rbxassetid://10709811706',['lucide-connection']='rbxassetid://10747361219',['lucide-contact']='rbxassetid://10709811834',['lucide-contrast']='rbxassetid://10709811939',['lucide-cookie']='rbxassetid://10709812067',['lucide-copy']='rbxassetid://10709812159',['lucide-copyleft']='rbxassetid://10709812251',['lucide-copyright']='rbxassetid://10709812311',['lucide-corner-down-left']='rbxassetid://10709812396',['lucide-corner-down-right']='rbxassetid://10709812485',['lucide-corner-left-down']='rbxassetid://10709812632',['lucide-corner-left-up']='rbxassetid://10709812784',['lucide-corner-right-down']='rbxassetid://10709812939',['lucide-corner-right-up']='rbxassetid://10709813094',['lucide-corner-up-left']='rbxassetid://10709813185',['lucide-corner-up-right']='rbxassetid://10709813281',['lucide-cpu']='rbxassetid://10709813383',['lucide-croissant']='rbxassetid://10709818125',['lucide-crop']='rbxassetid://10709818245',['lucide-cross']='rbxassetid://10709818399',['lucide-crosshair']='rbxassetid://10709818534',['lucide-crown']='rbxassetid://10709818626',['lucide-cup-soda']='rbxassetid://10709818763',['lucide-curly-braces']='rbxassetid://10709818847',['lucide-currency']='rbxassetid://10709818931',['lucide-database']='rbxassetid://10709818996',['lucide-delete']='rbxassetid://10709819059',['lucide-diamond']='rbxassetid://10709819149',['lucide-dice-1']='rbxassetid://10709819266',['lucide-dice-2']='rbxassetid://10709819361',['lucide-dice-3']='rbxassetid://10709819508',['lucide-dice-4']='rbxassetid://10709819670',['lucide-dice-5']='rbxassetid://10709819801',['lucide-dice-6']='rbxassetid://10709819896',['lucide-dices']='rbxassetid://10723343321',['lucide-diff']='rbxassetid://10723343416',['lucide-disc']='rbxassetid://10723343537',['lucide-divide']='rbxassetid://10723343805',['lucide-divide-circle']='rbxassetid://10723343636',['lucide-divide-square']='rbxassetid://10723343737',['lucide-dollar-sign']='rbxassetid://10723343958',['lucide-download']='rbxassetid://10723344270',['lucide-download-cloud']='rbxassetid://10723344088',['lucide-droplet']='rbxassetid://10723344432',['lucide-droplets']='rbxassetid://10734883356',['lucide-drumstick']='rbxassetid://10723344737',['lucide-edit']='rbxassetid://10734883598',['lucide-edit-2']='rbxassetid://10723344885',['lucide-edit-3']='rbxassetid://10723345088',['lucide-egg']='rbxassetid://10723345518',['lucide-egg-fried']='rbxassetid://10723345347',['lucide-electricity']='rbxassetid://10723345749',['lucide-electricity-off']='rbxassetid://10723345643',['lucide-equal']='rbxassetid://10723345990',['lucide-equal-not']='rbxassetid://10723345866',['lucide-eraser']='rbxassetid://10723346158',['lucide-euro']='rbxassetid://10723346372',['lucide-expand']='rbxassetid://10723346553',['lucide-external-link']='rbxassetid://10723346684',['lucide-eye']='rbxassetid://10723346959',['lucide-eye-off']='rbxassetid://10723346871',['lucide-factory']='rbxassetid://10723347051',['lucide-fan']='rbxassetid://10723354359',['lucide-fast-forward']='rbxassetid://10723354521',['lucide-feather']='rbxassetid://10723354671',['lucide-figma']='rbxassetid://10723354801',['lucide-file']='rbxassetid://10723374641',['lucide-file-archive']='rbxassetid://10723354921',['lucide-file-audio']='rbxassetid://10723355148',['lucide-file-audio-2']='rbxassetid://10723355026',['lucide-file-axis-3d']='rbxassetid://10723355272',['lucide-file-badge']='rbxassetid://10723355622',['lucide-file-badge-2']='rbxassetid://10723355451',['lucide-file-bar-chart']='rbxassetid://10723355887',['lucide-file-bar-chart-2']='rbxassetid://10723355746',['lucide-file-box']='rbxassetid://10723355989',['lucide-file-check']='rbxassetid://10723356210',['lucide-file-check-2']='rbxassetid://10723356100',['lucide-file-clock']='rbxassetid://10723356329',['lucide-file-code']='rbxassetid://10723356507',['lucide-file-cog']='rbxassetid://10723356830',['lucide-file-cog-2']='rbxassetid://10723356676',['lucide-file-diff']='rbxassetid://10723357039',['lucide-file-digit']='rbxassetid://10723357151',['lucide-file-down']='rbxassetid://10723357322',['lucide-file-edit']='rbxassetid://10723357495',['lucide-file-heart']='rbxassetid://10723357637',['lucide-file-image']='rbxassetid://10723357790',['lucide-file-input']='rbxassetid://10723357933',['lucide-file-json']='rbxassetid://10723364435',['lucide-file-json-2']='rbxassetid://10723364361',['lucide-file-key']='rbxassetid://10723364605',['lucide-file-key-2']='rbxassetid://10723364515',['lucide-file-line-chart']='rbxassetid://10723364725',['lucide-file-lock']='rbxassetid://10723364957',['lucide-file-lock-2']='rbxassetid://10723364861',['lucide-file-minus']='rbxassetid://10723365254',['lucide-file-minus-2']='rbxassetid://10723365086',['lucide-file-output']='rbxassetid://10723365457',['lucide-file-pie-chart']='rbxassetid://10723365598',['lucide-file-plus']='rbxassetid://10723365877',['lucide-file-plus-2']='rbxassetid://10723365766',['lucide-file-question']='rbxassetid://10723365987',['lucide-file-scan']='rbxassetid://10723366167',['lucide-file-search']='rbxassetid://10723366550',['lucide-file-search-2']='rbxassetid://10723366340',['lucide-file-signature']='rbxassetid://10723366741',['lucide-file-spreadsheet']='rbxassetid://10723366962',['lucide-file-symlink']='rbxassetid://10723367098',['lucide-file-terminal']='rbxassetid://10723367244',['lucide-file-text']='rbxassetid://10723367380',['lucide-file-type']='rbxassetid://10723367606',['lucide-file-type-2']='rbxassetid://10723367509',['lucide-file-up']='rbxassetid://10723367734',['lucide-file-video']='rbxassetid://10723373884',['lucide-file-video-2']='rbxassetid://10723367834',['lucide-file-volume']='rbxassetid://10723374172',['lucide-file-volume-2']='rbxassetid://10723374030',['lucide-file-warning']='rbxassetid://10723374276',['lucide-file-x']='rbxassetid://10723374544',['lucide-file-x-2']='rbxassetid://10723374378',['lucide-files']='rbxassetid://10723374759',['lucide-film']='rbxassetid://10723374981',['lucide-filter']='rbxassetid://10723375128',['lucide-fingerprint']='rbxassetid://10723375250',['lucide-flag']='rbxassetid://10723375890',['lucide-flag-off']='rbxassetid://10723375443',['lucide-flag-triangle-left']='rbxassetid://10723375608',['lucide-flag-triangle-right']='rbxassetid://10723375727',['lucide-flame']='rbxassetid://10723376114',['lucide-flashlight']='rbxassetid://10723376471',['lucide-flashlight-off']='rbxassetid://10723376365',['lucide-flask-conical']='rbxassetid://10734883986',['lucide-flask-round']='rbxassetid://10723376614',['lucide-flip-horizontal']='rbxassetid://10723376884',['lucide-flip-horizontal-2']='rbxassetid://10723376745',['lucide-flip-vertical']='rbxassetid://10723377138',['lucide-flip-vertical-2']='rbxassetid://10723377026',['lucide-flower']='rbxassetid://10747830374',['lucide-flower-2']='rbxassetid://10723377305',['lucide-focus']='rbxassetid://10723377537',['lucide-folder']='rbxassetid://10723387563',['lucide-folder-archive']='rbxassetid://10723384478',['lucide-folder-check']='rbxassetid://10723384605',['lucide-folder-clock']='rbxassetid://10723384731',['lucide-folder-closed']='rbxassetid://10723384893',['lucide-folder-cog']='rbxassetid://10723385213',['lucide-folder-cog-2']='rbxassetid://10723385036',['lucide-folder-down']='rbxassetid://10723385338',['lucide-folder-edit']='rbxassetid://10723385445',['lucide-folder-heart']='rbxassetid://10723385545',['lucide-folder-input']='rbxassetid://10723385721',['lucide-folder-key']='rbxassetid://10723385848',['lucide-folder-lock']='rbxassetid://10723386005',['lucide-folder-minus']='rbxassetid://10723386127',['lucide-folder-open']='rbxassetid://10723386277',['lucide-folder-output']='rbxassetid://10723386386',['lucide-folder-plus']='rbxassetid://10723386531',['lucide-folder-search']='rbxassetid://10723386787',['lucide-folder-search-2']='rbxassetid://10723386674',['lucide-folder-symlink']='rbxassetid://10723386930',['lucide-folder-tree']='rbxassetid://10723387085',['lucide-folder-up']='rbxassetid://10723387265',['lucide-folder-x']='rbxassetid://10723387448',['lucide-folders']='rbxassetid://10723387721',['lucide-form-input']='rbxassetid://10723387841',['lucide-forward']='rbxassetid://10723388016',['lucide-frame']='rbxassetid://10723394389',['lucide-framer']='rbxassetid://10723394565',['lucide-frown']='rbxassetid://10723394681',['lucide-fuel']='rbxassetid://10723394846',['lucide-function-square']='rbxassetid://10723395041',['lucide-gamepad']='rbxassetid://10723395457',['lucide-gamepad-2']='rbxassetid://10723395215',['lucide-gauge']='rbxassetid://10723395708',['lucide-gavel']='rbxassetid://10723395896',['lucide-gem']='rbxassetid://10723396000',['lucide-ghost']='rbxassetid://10723396107',['lucide-gift']='rbxassetid://10723396402',['lucide-gift-card']='rbxassetid://10723396225',['lucide-git-branch']='rbxassetid://10723396676',['lucide-git-branch-plus']='rbxassetid://10723396542',['lucide-git-commit']='rbxassetid://10723396812',['lucide-git-compare']='rbxassetid://10723396954',['lucide-git-fork']='rbxassetid://10723397049',['lucide-git-merge']='rbxassetid://10723397165',['lucide-git-pull-request']='rbxassetid://10723397431',['lucide-git-pull-request-closed']='rbxassetid://10723397268',['lucide-git-pull-request-draft']='rbxassetid://10734884302',['lucide-glass']='rbxassetid://10723397788',['lucide-glass-2']='rbxassetid://10723397529',['lucide-glass-water']='rbxassetid://10723397678',['lucide-glasses']='rbxassetid://10723397895',['lucide-globe']='rbxassetid://10723404337',['lucide-globe-2']='rbxassetid://10723398002',['lucide-grab']='rbxassetid://10723404472',['lucide-graduation-cap']='rbxassetid://10723404691',['lucide-grape']='rbxassetid://10723404822',['lucide-grid']='rbxassetid://10723404936',['lucide-grip-horizontal']='rbxassetid://10723405089',['lucide-grip-vertical']='rbxassetid://10723405236',['lucide-hammer']='rbxassetid://10723405360',['lucide-hand']='rbxassetid://10723405649',['lucide-hand-metal']='rbxassetid://10723405508',['lucide-hard-drive']='rbxassetid://10723405749',['lucide-hard-hat']='rbxassetid://10723405859',['lucide-hash']='rbxassetid://10723405975',['lucide-haze']='rbxassetid://10723406078',['lucide-headphones']='rbxassetid://10723406165',['lucide-heart']='rbxassetid://10723406885',['lucide-heart-crack']='rbxassetid://10723406299',['lucide-heart-handshake']='rbxassetid://10723406480',['lucide-heart-off']='rbxassetid://10723406662',['lucide-heart-pulse']='rbxassetid://10723406795',['lucide-help-circle']='rbxassetid://10723406988',['lucide-hexagon']='rbxassetid://10723407092',['lucide-highlighter']='rbxassetid://10723407192',['lucide-history']='rbxassetid://10723407335',['lucide-home']='rbxassetid://10723407389',['lucide-hourglass']='rbxassetid://10723407498',['lucide-ice-cream']='rbxassetid://10723414308',['lucide-image']='rbxassetid://10723415040',['lucide-image-minus']='rbxassetid://10723414487',['lucide-image-off']='rbxassetid://10723414677',['lucide-image-plus']='rbxassetid://10723414827',['lucide-import']='rbxassetid://10723415205',['lucide-inbox']='rbxassetid://10723415335',['lucide-indent']='rbxassetid://10723415494',['lucide-indian-rupee']='rbxassetid://10723415642',['lucide-infinity']='rbxassetid://10723415766',['lucide-info']='rbxassetid://10723415903',['lucide-inspect']='rbxassetid://10723416057',['lucide-italic']='rbxassetid://10723416195',['lucide-japanese-yen']='rbxassetid://10723416363',['lucide-joystick']='rbxassetid://10723416527',['lucide-key']='rbxassetid://10723416652',['lucide-keyboard']='rbxassetid://10723416765',['lucide-lamp']='rbxassetid://10723417513',['lucide-lamp-ceiling']='rbxassetid://10723416922',['lucide-lamp-desk']='rbxassetid://10723417016',['lucide-lamp-floor']='rbxassetid://10723417131',['lucide-lamp-wall-down']='rbxassetid://10723417240',['lucide-lamp-wall-up']='rbxassetid://10723417356',['lucide-landmark']='rbxassetid://10723417608',['lucide-languages']='rbxassetid://10723417703',['lucide-laptop']='rbxassetid://10723423881',['lucide-laptop-2']='rbxassetid://10723417797',['lucide-lasso']='rbxassetid://10723424235',['lucide-lasso-select']='rbxassetid://10723424058',['lucide-laugh']='rbxassetid://10723424372',['lucide-layers']='rbxassetid://10723424505',['lucide-layout']='rbxassetid://10723425376',['lucide-layout-dashboard']='rbxassetid://10723424646',['lucide-layout-grid']='rbxassetid://10723424838',['lucide-layout-list']='rbxassetid://10723424963',['lucide-layout-template']='rbxassetid://10723425187',['lucide-leaf']='rbxassetid://10723425539',['lucide-library']='rbxassetid://10723425615',['lucide-life-buoy']='rbxassetid://10723425685',['lucide-lightbulb']='rbxassetid://10723425852',['lucide-lightbulb-off']='rbxassetid://10723425762',['lucide-line-chart']='rbxassetid://10723426393',['lucide-link']='rbxassetid://10723426722',['lucide-link-2']='rbxassetid://10723426595',['lucide-link-2-off']='rbxassetid://10723426513',['lucide-list']='rbxassetid://10723433811',['lucide-list-checks']='rbxassetid://10734884548',['lucide-list-end']='rbxassetid://10723426886',['lucide-list-minus']='rbxassetid://10723426986',['lucide-list-music']='rbxassetid://10723427081',['lucide-list-ordered']='rbxassetid://10723427199',['lucide-list-plus']='rbxassetid://10723427334',['lucide-list-start']='rbxassetid://10723427494',['lucide-list-video']='rbxassetid://10723427619',['lucide-list-x']='rbxassetid://10723433655',['lucide-loader']='rbxassetid://10723434070',['lucide-loader-2']='rbxassetid://10723433935',['lucide-locate']='rbxassetid://10723434557',['lucide-locate-fixed']='rbxassetid://10723434236',['lucide-locate-off']='rbxassetid://10723434379',['lucide-lock']='rbxassetid://10723434711',['lucide-log-in']='rbxassetid://10723434830',['lucide-log-out']='rbxassetid://10723434906',['lucide-luggage']='rbxassetid://10723434993',['lucide-magnet']='rbxassetid://10723435069',['lucide-mail']='rbxassetid://10734885430',['lucide-mail-check']='rbxassetid://10723435182',['lucide-mail-minus']='rbxassetid://10723435261',['lucide-mail-open']='rbxassetid://10723435342',['lucide-mail-plus']='rbxassetid://10723435443',['lucide-mail-question']='rbxassetid://10723435515',['lucide-mail-search']='rbxassetid://10734884739',['lucide-mail-warning']='rbxassetid://10734885015',['lucide-mail-x']='rbxassetid://10734885247',['lucide-mails']='rbxassetid://10734885614',['lucide-map']='rbxassetid://10734886202',['lucide-map-pin']='rbxassetid://10734886004',['lucide-map-pin-off']='rbxassetid://10734885803',['lucide-maximize']='rbxassetid://10734886735',['lucide-maximize-2']='rbxassetid://10734886496',['lucide-medal']='rbxassetid://10734887072',['lucide-megaphone']='rbxassetid://10734887454',['lucide-megaphone-off']='rbxassetid://10734887311',['lucide-meh']='rbxassetid://10734887603',['lucide-menu']='rbxassetid://10734887784',['lucide-message-circle']='rbxassetid://10734888000',['lucide-message-square']='rbxassetid://10734888228',['lucide-mic']='rbxassetid://10734888864',['lucide-mic-2']='rbxassetid://10734888430',['lucide-mic-off']='rbxassetid://10734888646',['lucide-microscope']='rbxassetid://10734889106',['lucide-microwave']='rbxassetid://10734895076',['lucide-milestone']='rbxassetid://10734895310',['lucide-minimize']='rbxassetid://10734895698',['lucide-minimize-2']='rbxassetid://10734895530',['lucide-minus']='rbxassetid://10734896206',['lucide-minus-circle']='rbxassetid://10734895856',['lucide-minus-square']='rbxassetid://10734896029',['lucide-monitor']='rbxassetid://10734896881',['lucide-monitor-off']='rbxassetid://10734896360',['lucide-monitor-speaker']='rbxassetid://10734896512',['lucide-moon']='rbxassetid://10734897102',['lucide-more-horizontal']='rbxassetid://10734897250',['lucide-more-vertical']='rbxassetid://10734897387',['lucide-mountain']='rbxassetid://10734897956',['lucide-mountain-snow']='rbxassetid://10734897665',['lucide-mouse']='rbxassetid://10734898592',['lucide-mouse-pointer']='rbxassetid://10734898476',['lucide-mouse-pointer-2']='rbxassetid://10734898194',['lucide-mouse-pointer-click']='rbxassetid://10734898355',['lucide-move']='rbxassetid://10734900011',['lucide-move-3d']='rbxassetid://10734898756',['lucide-move-diagonal']='rbxassetid://10734899164',['lucide-move-diagonal-2']='rbxassetid://10734898934',['lucide-move-horizontal']='rbxassetid://10734899414',['lucide-move-vertical']='rbxassetid://10734899821',['lucide-music']='rbxassetid://10734905958',['lucide-music-2']='rbxassetid://10734900215',['lucide-music-3']='rbxassetid://10734905665',['lucide-music-4']='rbxassetid://10734905823',['lucide-navigation']='rbxassetid://10734906744',['lucide-navigation-2']='rbxassetid://10734906332',['lucide-navigation-2-off']='rbxassetid://10734906144',['lucide-navigation-off']='rbxassetid://10734906580',['lucide-network']='rbxassetid://10734906975',['lucide-newspaper']='rbxassetid://10734907168',['lucide-octagon']='rbxassetid://10734907361',['lucide-option']='rbxassetid://10734907649',['lucide-outdent']='rbxassetid://10734907933',['lucide-package']='rbxassetid://10734909540',['lucide-package-2']='rbxassetid://10734908151',['lucide-package-check']='rbxassetid://10734908384',['lucide-package-minus']='rbxassetid://10734908626',['lucide-package-open']='rbxassetid://10734908793',['lucide-package-plus']='rbxassetid://10734909016',['lucide-package-search']='rbxassetid://10734909196',['lucide-package-x']='rbxassetid://10734909375',['lucide-paint-bucket']='rbxassetid://10734909847',['lucide-paintbrush']='rbxassetid://10734910187',['lucide-paintbrush-2']='rbxassetid://10734910030',['lucide-palette']='rbxassetid://10734910430',['lucide-palmtree']='rbxassetid://10734910680',['lucide-paperclip']='rbxassetid://10734910927',['lucide-party-popper']='rbxassetid://10734918735',['lucide-pause']='rbxassetid://10734919336',['lucide-pause-circle']='rbxassetid://10735024209',['lucide-pause-octagon']='rbxassetid://10734919143',['lucide-pen-tool']='rbxassetid://10734919503',['lucide-pencil']='rbxassetid://10734919691',['lucide-percent']='rbxassetid://10734919919',['lucide-person-standing']='rbxassetid://10734920149',['lucide-phone']='rbxassetid://10734921524',['lucide-phone-call']='rbxassetid://10734920305',['lucide-phone-forwarded']='rbxassetid://10734920508',['lucide-phone-incoming']='rbxassetid://10734920694',['lucide-phone-missed']='rbxassetid://10734920845',['lucide-phone-off']='rbxassetid://10734921077',['lucide-phone-outgoing']='rbxassetid://10734921288',['lucide-pie-chart']='rbxassetid://10734921727',['lucide-piggy-bank']='rbxassetid://10734921935',['lucide-pin']='rbxassetid://10734922324',['lucide-pin-off']='rbxassetid://10734922180',['lucide-pipette']='rbxassetid://10734922497',['lucide-pizza']='rbxassetid://10734922774',['lucide-plane']='rbxassetid://10734922971',['lucide-play']='rbxassetid://10734923549',['lucide-play-circle']='rbxassetid://10734923214',['lucide-plus']='rbxassetid://10734924532',['lucide-plus-circle']='rbxassetid://10734923868',['lucide-plus-square']='rbxassetid://10734924219',['lucide-podcast']='rbxassetid://10734929553',['lucide-pointer']='rbxassetid://10734929723',['lucide-pound-sterling']='rbxassetid://10734929981',['lucide-power']='rbxassetid://10734930466',['lucide-power-off']='rbxassetid://10734930257',['lucide-printer']='rbxassetid://10734930632',['lucide-puzzle']='rbxassetid://10734930886',['lucide-quote']='rbxassetid://10734931234',['lucide-radio']='rbxassetid://10734931596',['lucide-radio-receiver']='rbxassetid://10734931402',['lucide-rectangle-horizontal']='rbxassetid://10734931777',['lucide-rectangle-vertical']='rbxassetid://10734932081',['lucide-recycle']='rbxassetid://10734932295',['lucide-redo']='rbxassetid://10734932822',['lucide-redo-2']='rbxassetid://10734932586',['lucide-refresh-ccw']='rbxassetid://10734933056',['lucide-refresh-cw']='rbxassetid://10734933222',['lucide-refrigerator']='rbxassetid://10734933465',['lucide-regex']='rbxassetid://10734933655',['lucide-repeat']='rbxassetid://10734933966',['lucide-repeat-1']='rbxassetid://10734933826',['lucide-reply']='rbxassetid://10734934252',['lucide-reply-all']='rbxassetid://10734934132',['lucide-rewind']='rbxassetid://10734934347',['lucide-rocket']='rbxassetid://10734934585',['lucide-rocking-chair']='rbxassetid://10734939942',['lucide-rotate-3d']='rbxassetid://10734940107',['lucide-rotate-ccw']='rbxassetid://10734940376',['lucide-rotate-cw']='rbxassetid://10734940654',['lucide-rss']='rbxassetid://10734940825',['lucide-ruler']='rbxassetid://10734941018',['lucide-russian-ruble']='rbxassetid://10734941199',['lucide-sailboat']='rbxassetid://10734941354',['lucide-save']='rbxassetid://10734941499',['lucide-scale']='rbxassetid://10734941912',['lucide-scale-3d']='rbxassetid://10734941739',['lucide-scaling']='rbxassetid://10734942072',['lucide-scan']='rbxassetid://10734942565',['lucide-scan-face']='rbxassetid://10734942198',['lucide-scan-line']='rbxassetid://10734942351',['lucide-scissors']='rbxassetid://10734942778',['lucide-screen-share']='rbxassetid://10734943193',['lucide-screen-share-off']='rbxassetid://10734942967',['lucide-scroll']='rbxassetid://10734943448',['lucide-search']='rbxassetid://10734943674',['lucide-send']='rbxassetid://10734943902',['lucide-separator-horizontal']='rbxassetid://10734944115',['lucide-separator-vertical']='rbxassetid://10734944326',['lucide-server']='rbxassetid://10734949856',['lucide-server-cog']='rbxassetid://10734944444',['lucide-server-crash']='rbxassetid://10734944554',['lucide-server-off']='rbxassetid://10734944668',['lucide-settings']='rbxassetid://10734950309',['lucide-settings-2']='rbxassetid://10734950020',['lucide-share']='rbxassetid://10734950813',['lucide-share-2']='rbxassetid://10734950553',['lucide-sheet']='rbxassetid://10734951038',['lucide-shield']='rbxassetid://10734951847',['lucide-shield-alert']='rbxassetid://10734951173',['lucide-shield-check']='rbxassetid://10734951367',['lucide-shield-close']='rbxassetid://10734951535',['lucide-shield-off']='rbxassetid://10734951684',['lucide-shirt']='rbxassetid://10734952036',['lucide-shopping-bag']='rbxassetid://10734952273',['lucide-shopping-cart']='rbxassetid://10734952479',['lucide-shovel']='rbxassetid://10734952773',['lucide-shower-head']='rbxassetid://10734952942',['lucide-shrink']='rbxassetid://10734953073',['lucide-shrub']='rbxassetid://10734953241',['lucide-shuffle']='rbxassetid://10734953451',['lucide-sidebar']='rbxassetid://10734954301',['lucide-sidebar-close']='rbxassetid://10734953715',['lucide-sidebar-open']='rbxassetid://10734954000',['lucide-sigma']='rbxassetid://10734954538',['lucide-signal']='rbxassetid://10734961133',['lucide-signal-high']='rbxassetid://10734954807',['lucide-signal-low']='rbxassetid://10734955080',['lucide-signal-medium']='rbxassetid://10734955336',['lucide-signal-zero']='rbxassetid://10734960878',['lucide-siren']='rbxassetid://10734961284',['lucide-skip-back']='rbxassetid://10734961526',['lucide-skip-forward']='rbxassetid://10734961809',['lucide-skull']='rbxassetid://10734962068',['lucide-slack']='rbxassetid://10734962339',['lucide-slash']='rbxassetid://10734962600',['lucide-slice']='rbxassetid://10734963024',['lucide-sliders']='rbxassetid://10734963400',['lucide-sliders-horizontal']='rbxassetid://10734963191',['lucide-smartphone']='rbxassetid://10734963940',['lucide-smartphone-charging']='rbxassetid://10734963671',['lucide-smile']='rbxassetid://10734964441',['lucide-smile-plus']='rbxassetid://10734964188',['lucide-snowflake']='rbxassetid://10734964600',['lucide-sofa']='rbxassetid://10734964852',['lucide-sort-asc']='rbxassetid://10734965115',['lucide-sort-desc']='rbxassetid://10734965287',['lucide-speaker']='rbxassetid://10734965419',['lucide-sprout']='rbxassetid://10734965572',['lucide-square']='rbxassetid://10734965702',['lucide-star']='rbxassetid://10734966248',['lucide-star-half']='rbxassetid://10734965897',['lucide-star-off']='rbxassetid://10734966097',['lucide-stethoscope']='rbxassetid://10734966384',['lucide-sticker']='rbxassetid://10734972234',['lucide-sticky-note']='rbxassetid://10734972463',['lucide-stop-circle']='rbxassetid://10734972621',['lucide-stretch-horizontal']='rbxassetid://10734972862',['lucide-stretch-vertical']='rbxassetid://10734973130',['lucide-strikethrough']='rbxassetid://10734973290',['lucide-subscript']='rbxassetid://10734973457',['lucide-sun']='rbxassetid://10734974297',['lucide-sun-dim']='rbxassetid://10734973645',['lucide-sun-medium']='rbxassetid://10734973778',['lucide-sun-moon']='rbxassetid://10734973999',['lucide-sun-snow']='rbxassetid://10734974130',['lucide-sunrise']='rbxassetid://10734974522',['lucide-sunset']='rbxassetid://10734974689',['lucide-superscript']='rbxassetid://10734974850',['lucide-swiss-franc']='rbxassetid://10734975024',['lucide-switch-camera']='rbxassetid://10734975214',['lucide-sword']='rbxassetid://10734975486',['lucide-swords']='rbxassetid://10734975692',['lucide-syringe']='rbxassetid://10734975932',['lucide-table']='rbxassetid://10734976230',['lucide-table-2']='rbxassetid://10734976097',['lucide-tablet']='rbxassetid://10734976394',['lucide-tag']='rbxassetid://10734976528',['lucide-tags']='rbxassetid://10734976739',['lucide-target']='rbxassetid://10734977012',['lucide-tent']='rbxassetid://10734981750',['lucide-terminal']='rbxassetid://10734982144',['lucide-terminal-square']='rbxassetid://10734981995',['lucide-text-cursor']='rbxassetid://10734982395',['lucide-text-cursor-input']='rbxassetid://10734982297',['lucide-thermometer']='rbxassetid://10734983134',['lucide-thermometer-snowflake']='rbxassetid://10734982571',['lucide-thermometer-sun']='rbxassetid://10734982771',['lucide-thumbs-down']='rbxassetid://10734983359',['lucide-thumbs-up']='rbxassetid://10734983629',['lucide-ticket']='rbxassetid://10734983868',['lucide-timer']='rbxassetid://10734984606',['lucide-timer-off']='rbxassetid://10734984138',['lucide-timer-reset']='rbxassetid://10734984355',['lucide-toggle-left']='rbxassetid://10734984834',['lucide-toggle-right']='rbxassetid://10734985040',['lucide-tornado']='rbxassetid://10734985247',['lucide-toy-brick']='rbxassetid://10747361919',['lucide-train']='rbxassetid://10747362105',['lucide-trash']='rbxassetid://10747362393',['lucide-trash-2']='rbxassetid://10747362241',['lucide-tree-deciduous']='rbxassetid://10747362534',['lucide-tree-pine']='rbxassetid://10747362748',['lucide-trees']='rbxassetid://10747363016',['lucide-trending-down']='rbxassetid://10747363205',['lucide-trending-up']='rbxassetid://10747363465',['lucide-triangle']='rbxassetid://10747363621',['lucide-trophy']='rbxassetid://10747363809',['lucide-truck']='rbxassetid://10747364031',['lucide-tv']='rbxassetid://10747364593',['lucide-tv-2']='rbxassetid://10747364302',['lucide-type']='rbxassetid://10747364761',['lucide-umbrella']='rbxassetid://10747364971',['lucide-underline']='rbxassetid://10747365191',['lucide-undo']='rbxassetid://10747365484',['lucide-undo-2']='rbxassetid://10747365359',['lucide-unlink']='rbxassetid://10747365771',['lucide-unlink-2']='rbxassetid://10747397871',['lucide-unlock']='rbxassetid://10747366027',['lucide-upload']='rbxassetid://10747366434',['lucide-upload-cloud']='rbxassetid://10747366266',['lucide-usb']='rbxassetid://10747366606',['lucide-user']='rbxassetid://10747373176',['lucide-user-check']='rbxassetid://10747371901',['lucide-user-cog']='rbxassetid://10747372167',['lucide-user-minus']='rbxassetid://10747372346',['lucide-user-plus']='rbxassetid://10747372702',['lucide-user-x']='rbxassetid://10747372992',['lucide-users']='rbxassetid://10747373426',['lucide-utensils']='rbxassetid://10747373821',['lucide-utensils-crossed']='rbxassetid://10747373629',['lucide-venetian-mask']='rbxassetid://10747374003',['lucide-verified']='rbxassetid://10747374131',['lucide-vibrate']='rbxassetid://10747374489',['lucide-vibrate-off']='rbxassetid://10747374269',['lucide-video']='rbxassetid://10747374938',['lucide-video-off']='rbxassetid://10747374721',['lucide-view']='rbxassetid://10747375132',['lucide-voicemail']='rbxassetid://10747375281',['lucide-volume']='rbxassetid://10747376008',['lucide-volume-1']='rbxassetid://10747375450',['lucide-volume-2']='rbxassetid://10747375679',['lucide-volume-x']='rbxassetid://10747375880',['lucide-wallet']='rbxassetid://10747376205',['lucide-wand']='rbxassetid://10747376565',['lucide-wand-2']='rbxassetid://10747376349',['lucide-watch']='rbxassetid://10747376722',['lucide-waves']='rbxassetid://10747376931',['lucide-webcam']='rbxassetid://10747381992',['lucide-wifi']='rbxassetid://10747382504',['lucide-wifi-off']='rbxassetid://10747382268',['lucide-wind']='rbxassetid://10747382750',['lucide-wrap-text']='rbxassetid://10747383065',['lucide-wrench']='rbxassetid://10747383470',['lucide-x']='rbxassetid://10747384394',['lucide-x-circle']='rbxassetid://10747383819',['lucide-x-octagon']='rbxassetid://10747384037',['lucide-x-square']='rbxassetid://10747384217',['lucide-zoom-in']='rbxassetid://10747384552',['lucide-zoom-out']='rbxassetid://10747384679'}}end,[30]=function()local aa,ab,ac,ad,ae=b(30)local af={SingleMotor=ac(ab.SingleMotor),GroupMotor=ac(ab.GroupMotor),Instant=ac(ab.Instant),Linear=ac(ab.Linear),Spring=ac(ab.Spring),isMotor=ac(ab.isMotor)}return af end,[31]=function()local aa,ab,ac,ad,ae=b(31)local af,ag,ah,ai=game:GetService'RunService',ac(ab.Parent.Signal),function()end,{}ai.__index=ai function ai.new()return setmetatable({_onStep=ag.new(),_onStart=ag.new(),_onComplete=ag.new()},ai)end function ai.onStep(aj,c)return aj._onStep:connect(c)end function ai.onStart(aj,c)return aj._onStart:connect(c)end function ai.onComplete(aj,c)return aj._onComplete:connect(c)end function ai.start(aj)if not aj._connection then aj._connection=af.RenderStepped:Connect(function(c)aj:step(c)end)end end function ai.stop(aj)if aj._connection then aj._connection:Disconnect()aj._connection=nil end end ai.destroy=ai.stop ai.step=ah ai.getValue=ah ai.setGoal=ah function ai.__tostring(aj)return'Motor'end return ai end,[32]=function()local aa,ab,ac,ad,ae=b(32)return function()local af,ag=game:GetService'RunService',ac(ab.Parent.BaseMotor)describe('connection management',function()local ah=ag.new()it('should hook up connections on :start()',function()ah:start()expect(typeof(ah._connection)).to.equal'RBXScriptConnection'end)it('should remove connections on :stop() or :destroy()',function()ah:stop()expect(ah._connection).to.equal(nil)end)end)it('should call :step() with deltaTime',function()local ah,ai=(ag.new())function ah.step(aj,...)ai={...}ah:stop()end ah:start()local aj=af.RenderStepped:Wait()af.RenderStepped:Wait()expect(ai).to.be.ok()expect(ai[1]).to.equal(aj)end)end end,[33]=function()local aa,ab,ac,ad,ae=b(33)local af,ag,ah=ac(ab.Parent.BaseMotor),ac(ab.Parent.SingleMotor),ac(ab.Parent.isMotor)local ai=setmetatable({},af)ai.__index=ai local aj=function(aj)if ah(aj)then return aj end local c=typeof(aj)if c=='number'then return ag.new(aj,false)elseif c=='table'then return ai.new(aj,false)end error(('Unable to convert %q to motor; type %s is unsupported'):format(aj,c),2)end function ai.new(c,d)assert(c,'Missing argument #1: initialValues')assert(typeof(c)=='table','initialValues must be a table!')assert(not c.step,[[initialValues contains disallowed property "step". Did you mean to put a table of values here?]])local e=setmetatable(af.new(),ai)if d~=nil then e._useImplicitConnections=d else e._useImplicitConnections=true end e._complete=true e._motors={}for f,g in pairs(c)do e._motors[f]=aj(g)end return e end function ai.step(c,d)if c._complete then return true end local e=true for f,g in pairs(c._motors)do local h=g:step(d)if not h then e=false end end c._onStep:fire(c:getValue())if e then if c._useImplicitConnections then c:stop()end c._complete=true c._onComplete:fire()end return e end function ai.setGoal(c,d)assert(not d.step,[[goals contains disallowed property "step". Did you mean to put a table of goals here?]])c._complete=false c._onStart:fire()for e,f in pairs(d)do local g=assert(c._motors[e],('Unknown motor for key %s'):format(e))g:setGoal(f)end if c._useImplicitConnections then c:start()end end function ai.getValue(c)local d={}for e,f in pairs(c._motors)do d[e]=f:getValue()end return d end function ai.__tostring(c)return'Motor(Group)'end return ai end,[34]=function()local aa,ab,ac,ad,ae=b(34)return function()local af,ag,ah=ac(ab.Parent.GroupMotor),ac(ab.Parent.Instant),ac(ab.Parent.Spring)it('should complete when all child motors are complete',function()local ai=af.new({A=1,B=2},false)expect(ai._complete).to.equal(true)ai:setGoal{A=ag.new(3),B=ah.new(4,{frequency=7.5,dampingRatio=1})}expect(ai._complete).to.equal(false)ai:step(1.6666666666666665E-2)expect(ai._complete).to.equal(false)for aj=1,30 do ai:step(1.6666666666666665E-2)end expect(ai._complete).to.equal(true)end)it('should start when the goal is set',function()local ai,aj=af.new({A=0},false),false ai:onStart(function()aj=not aj end)ai:setGoal{A=ag.new(1)}expect(aj).to.equal(true)ai:setGoal{A=ag.new(1)}expect(aj).to.equal(false)end)it('should properly return all values',function()local ai=af.new({A=1,B=2},false)local aj=ai:getValue()expect(aj.A).to.equal(1)expect(aj.B).to.equal(2)end)it('should error when a goal is given to GroupMotor.new',function()local ai=pcall(function()af.new(ag.new(0))end)expect(ai).to.equal(false)end)it([[should error when a single goal is provided to GroupMotor:step]],function()local ai=pcall(function()af.new{a=1}:setGoal(ag.new(0))end)expect(ai).to.equal(false)end)end end,[35]=function()local aa,ab,ac,ad,ae=b(35)local af={}af.__index=af function af.new(ag)return setmetatable({_targetValue=ag},af)end function af.step(ag)return{complete=true,value=ag._targetValue}end return af end,[36]=function()local aa,ab,ac,ad,ae=b(36)return function()local af=ac(ab.Parent.Instant)it('should return a completed state with the provided value',function()local ag=af.new(1.23)local ah=ag:step(0.1,{value=0,complete=false})expect(ah.complete).to.equal(true)expect(ah.value).to.equal(1.23)end)end end,[37]=function()local aa,ab,ac,ad,ae=b(37)local af={}af.__index=af function af.new(ag,ah)assert(ag,'Missing argument #1: targetValue')ah=ah or{}return setmetatable({_targetValue=ag,_velocity=ah.velocity or 1},af)end function af.step(ag,ah,ai)local aj,c,d=ah.value,ag._velocity,ag._targetValue local e=ai*c local f=e>=math.abs(d-aj)aj=aj+e*(d>aj and 1 or-1)if f then aj=ag._targetValue c=0 end return{complete=f,value=aj,velocity=c}end return af end,[38]=function()local aa,ab,ac,ad,ae=b(38)return function()local af,ag=ac(ab.Parent.SingleMotor),ac(ab.Parent.Linear)describe('completed state',function()local ah,ai=af.new(0,false),ag.new(1,{velocity=1})ah:setGoal(ai)for aj=1,60 do ah:step(1.6666666666666665E-2)end it('should complete',function()expect(ah._state.complete).to.equal(true)end)it('should be exactly the goal value when completed',function()expect(ah._state.value).to.equal(1)end)end)describe('uncompleted state',function()local ah,ai=af.new(0,false),ag.new(1,{velocity=1})ah:setGoal(ai)for aj=1,59 do ah:step(1.6666666666666665E-2)end it('should be uncomplete',function()expect(ah._state.complete).to.equal(false)end)end)describe('negative velocity',function()local ah,ai=af.new(1,false),ag.new(0,{velocity=1})ah:setGoal(ai)for aj=1,60 do ah:step(1.6666666666666665E-2)end it('should complete',function()expect(ah._state.complete).to.equal(true)end)it('should be exactly the goal value when completed',function()expect(ah._state.value).to.equal(0)end)end)end end,[39]=function()local aa,ab,ac,ad,ae=b(39)local af={}af.__index=af function af.new(ag,ah)return setmetatable({signal=ag,connected=true,_handler=ah},af)end function af.disconnect(ag)if ag.connected then ag.connected=false for ah,ai in pairs(ag.signal._connections)do if ai==ag then table.remove(ag.signal._connections,ah)return end end end end local ag={}ag.__index=ag function ag.new()return setmetatable({_connections={},_threads={}},ag)end function ag.fire(ah,...)for ai,aj in pairs(ah._connections)do aj._handler(...)end for c,d in pairs(ah._threads)do coroutine.resume(d,...)end ah._threads={}end function ag.connect(ah,aj)local c=af.new(ah,aj)table.insert(ah._connections,c)return c end function ag.wait(ah)table.insert(ah._threads,coroutine.running())return coroutine.yield()end return ag end,[40]=function()local aa,ab,ac,ad,ae=b(40)return function()local af=ac(ab.Parent.Signal)it('should invoke all connections, instantly',function()local ag,ah,aj=(af.new())ag:connect(function(c)ah=c end)ag:connect(function(c)aj=c end)ag:fire'hello'expect(ah).to.equal'hello'expect(aj).to.equal'hello'end)it('should return values when :wait() is called',function()local ag=af.new()spawn(function()ag:fire(123,'hello')end)local ah,aj=ag:wait()expect(ah).to.equal(123)expect(aj).to.equal'hello'end)it('should properly handle disconnections',function()local ag,ah=af.new(),false local aj=ag:connect(function()ah=true end)aj:disconnect()ag:fire()expect(ah).to.equal(false)end)end end,[41]=function()local aa,ab,ac,ad,ae=b(41)local af=ac(ab.Parent.BaseMotor)local ag=setmetatable({},af)ag.__index=ag function ag.new(ah,aj)assert(ah,'Missing argument #1: initialValue')assert(typeof(ah)=='number','initialValue must be a number!')local c=setmetatable(af.new(),ag)if aj~=nil then c._useImplicitConnections=aj else c._useImplicitConnections=true end c._goal=nil c._state={complete=true,value=ah}return c end function ag.step(ah,aj)if ah._state.complete then return true end local c=ah._goal:step(ah._state,aj)ah._state=c ah._onStep:fire(c.value)if c.complete then if ah._useImplicitConnections then ah:stop()end ah._onComplete:fire()end return c.complete end function ag.getValue(ah)return ah._state.value end function ag.setGoal(ah,aj)ah._state.complete=false ah._goal=aj ah._onStart:fire()if ah._useImplicitConnections then ah:start()end end function ag.__tostring(ah)return'Motor(Single)'end return ag end,[42]=function()local aa,ab,ac,ad,ae=b(42)return function()local af,ag=ac(ab.Parent.SingleMotor),ac(ab.Parent.Instant)it('should assign new state on step',function()local ah=af.new(0,false)ah:setGoal(ag.new(5))ah:step(1.6666666666666665E-2)expect(ah._state.complete).to.equal(true)expect(ah._state.value).to.equal(5)end)it([[should invoke onComplete listeners when the goal is completed]],function()local ah,aj=af.new(0,false),false ah:onComplete(function()aj=true end)ah:setGoal(ag.new(5))ah:step(1.6666666666666665E-2)expect(aj).to.equal(true)end)it('should start when the goal is set',function()local ah,aj=af.new(0,false),false ah:onStart(function()aj=not aj end)ah:setGoal(ag.new(5))expect(aj).to.equal(true)ah:setGoal(ag.new(5))expect(aj).to.equal(false)end)end end,[43]=function()local aa,ab,ac,ad,ae=b(43)local af,ag,ah,aj=0.001,0.001,0.0001,{}aj.__index=aj function aj.new(c,d)assert(c,'Missing argument #1: targetValue')d=d or{}return setmetatable({_targetValue=c,_frequency=d.frequency or 4,_dampingRatio=d.dampingRatio or 1},aj)end function aj.step(c,d,e)local f,g,h,i,j=c._dampingRatio,c._frequency*2*math.pi,c._targetValue,d.value,d.velocity or 0 local k,l,m,n=i-h,(math.exp(-f*g*e))if f==1 then m=(k*(1+g*e)+j*e)*l+h n=(j*(1-g*e)-k*(g*g*e))*l elseif f<1 then local o=math.sqrt(1-f*f)local p,s,t=math.cos(g*o*e),(math.sin(g*o*e))if o>ah then t=s/o else local u=e*g t=u+((u*u)*(o*o)*(o*o)/20-o*o)*(u*u*u)/6 end local u if g*o>ah then u=s/(g*o)else local v=g*o u=e+((e*e)*(v*v)*(v*v)/20-v*v)*(e*e*e)/6 end m=(k*(p+f*t)+j*u)*l+h n=(j*(p-t*f)-k*(t*g))*l else local o=math.sqrt(f*f-1)local p,s=-g*(f-o),-g*(f+o)local t=(j-k*p)/(2*g*o)local u=k-t local v,w=u*math.exp(p*e),t*math.exp(s*e)m=v+w+h n=v*p+w*s end local o=math.abs(n)<af and math.abs(m-h)<ag return{complete=o,value=o and h or m,velocity=n}end return aj end,[44]=function()local aa,ab,ac,ad,ae=b(44)return function()local af,ag=ac(ab.Parent.SingleMotor),ac(ab.Parent.Spring)describe('completed state',function()local ah,aj=af.new(0,false),ag.new(1,{frequency=2,dampingRatio=0.75})ah:setGoal(aj)for c=1,100 do ah:step(1.6666666666666665E-2)end it('should complete',function()expect(ah._state.complete).to.equal(true)end)it('should be exactly the goal value when completed',function()expect(ah._state.value).to.equal(1)end)end)it('should inherit velocity',function()local ah=af.new(0,false)ah._state={complete=false,value=0,velocity=-5}local aj=ag.new(1,{frequency=2,dampingRatio=1})ah:setGoal(aj)ah:step(1.6666666666666665E-2)expect(ah._state.velocity<0).to.equal(true)end)end end,[45]=function()local aa,ab,ac,ad,ae=b(45)local af=function(af)local ag=tostring(af):match'^Motor%((.+)%)$'if ag then return true,ag else return false end end return af end,[46]=function()local aa,ab,ac,ad,ae=b(46)return function()local af,ag,ah=ac(ab.Parent.isMotor),ac(ab.Parent.SingleMotor),ac(ab.Parent.GroupMotor)local aj,c=ag.new(0),ah.new{}it('should properly detect motors',function()expect(af(aj)).to.equal(true)expect(af(c)).to.equal(true)end)it("shouldn't detect things that aren't motors",function()expect(af{}).to.equal(false)end)it('should return the proper motor type',function()local d,e=af(aj)local f,g=af(c)expect(e).to.equal'Single'expect(g).to.equal'Group'end)end end,[47]=function()local aa,ab,ac,ad,ae=b(47)local af={Names={'Dark','Darker','Light','Aqua','Amethyst','Rose'}}for ag,ah in next,ab:GetChildren()do local aj=ac(ah)af[aj.Name]=aj end return af end,[48]=function()local aa,ab,ac,ad,ae=b(48)return{Name='Amethyst',Accent=Color3.fromRGB(97,62,167),AcrylicMain=Color3.fromRGB(20,20,20),AcrylicBorder=Color3.fromRGB(110,90,130),AcrylicGradient=ColorSequence.new(Color3.fromRGB(85,57,139),Color3.fromRGB(40,25,65)),AcrylicNoise=0.92,TitleBarLine=Color3.fromRGB(95,75,110),Tab=Color3.fromRGB(160,140,180),Element=Color3.fromRGB(140,120,160),ElementBorder=Color3.fromRGB(60,50,70),InElementBorder=Color3.fromRGB(100,90,110),ElementTransparency=0.87,ToggleSlider=Color3.fromRGB(140,120,160),ToggleToggled=Color3.fromRGB(0,0,0),SliderRail=Color3.fromRGB(140,120,160),DropdownFrame=Color3.fromRGB(170,160,200),DropdownHolder=Color3.fromRGB(60,45,80),DropdownBorder=Color3.fromRGB(50,40,65),DropdownOption=Color3.fromRGB(140,120,160),Keybind=Color3.fromRGB(140,120,160),Input=Color3.fromRGB(140,120,160),InputFocused=Color3.fromRGB(20,10,30),InputIndicator=Color3.fromRGB(170,150,190),Dialog=Color3.fromRGB(60,45,80),DialogHolder=Color3.fromRGB(45,30,65),DialogHolderLine=Color3.fromRGB(40,25,60),DialogButton=Color3.fromRGB(60,45,80),DialogButtonBorder=Color3.fromRGB(95,80,110),DialogBorder=Color3.fromRGB(85,70,100),DialogInput=Color3.fromRGB(70,55,85),DialogInputLine=Color3.fromRGB(175,160,190),Text=Color3.fromRGB(240,240,240),SubText=Color3.fromRGB(170,170,170),Hover=Color3.fromRGB(140,120,160),HoverChange=0.04}end,[49]=function()local aa,ab,ac,ad,ae=b(49)return{Name='Aqua',Accent=Color3.fromRGB(60,165,165),AcrylicMain=Color3.fromRGB(20,20,20),AcrylicBorder=Color3.fromRGB(50,100,100),AcrylicGradient=ColorSequence.new(Color3.fromRGB(60,140,140),Color3.fromRGB(40,80,80)),AcrylicNoise=0.92,TitleBarLine=Color3.fromRGB(60,120,120),Tab=Color3.fromRGB(140,180,180),Element=Color3.fromRGB(110,160,160),ElementBorder=Color3.fromRGB(40,70,70),InElementBorder=Color3.fromRGB(80,110,110),ElementTransparency=0.84,ToggleSlider=Color3.fromRGB(110,160,160),ToggleToggled=Color3.fromRGB(0,0,0),SliderRail=Color3.fromRGB(110,160,160),DropdownFrame=Color3.fromRGB(160,200,200),DropdownHolder=Color3.fromRGB(40,80,80),DropdownBorder=Color3.fromRGB(40,65,65),DropdownOption=Color3.fromRGB(110,160,160),Keybind=Color3.fromRGB(110,160,160),Input=Color3.fromRGB(110,160,160),InputFocused=Color3.fromRGB(20,10,30),InputIndicator=Color3.fromRGB(130,170,170),Dialog=Color3.fromRGB(40,80,80),DialogHolder=Color3.fromRGB(30,60,60),DialogHolderLine=Color3.fromRGB(25,50,50),DialogButton=Color3.fromRGB(40,80,80),DialogButtonBorder=Color3.fromRGB(80,110,110),DialogBorder=Color3.fromRGB(50,100,100),DialogInput=Color3.fromRGB(45,90,90),DialogInputLine=Color3.fromRGB(130,170,170),Text=Color3.fromRGB(240,240,240),SubText=Color3.fromRGB(170,170,170),Hover=Color3.fromRGB(110,160,160),HoverChange=0.04}end,[50]=function()local aa,ab,ac,ad,ae=b(50)return{Name='Dark',Accent=Color3.fromRGB(96,205,255),AcrylicMain=Color3.fromRGB(60,60,60),AcrylicBorder=Color3.fromRGB(90,90,90),AcrylicGradient=ColorSequence.new(Color3.fromRGB(40,40,40),Color3.fromRGB(40,40,40)),AcrylicNoise=0.9,TitleBarLine=Color3.fromRGB(75,75,75),Tab=Color3.fromRGB(120,120,120),Element=Color3.fromRGB(120,120,120),ElementBorder=Color3.fromRGB(35,35,35),InElementBorder=Color3.fromRGB(90,90,90),ElementTransparency=0.87,ToggleSlider=Color3.fromRGB(120,120,120),ToggleToggled=Color3.fromRGB(0,0,0),SliderRail=Color3.fromRGB(120,120,120),DropdownFrame=Color3.fromRGB(160,160,160),DropdownHolder=Color3.fromRGB(45,45,45),DropdownBorder=Color3.fromRGB(35,35,35),DropdownOption=Color3.fromRGB(120,120,120),Keybind=Color3.fromRGB(120,120,120),Input=Color3.fromRGB(160,160,160),InputFocused=Color3.fromRGB(10,10,10),InputIndicator=Color3.fromRGB(150,150,150),Dialog=Color3.fromRGB(45,45,45),DialogHolder=Color3.fromRGB(35,35,35),DialogHolderLine=Color3.fromRGB(30,30,30),DialogButton=Color3.fromRGB(45,45,45),DialogButtonBorder=Color3.fromRGB(80,80,80),DialogBorder=Color3.fromRGB(70,70,70),DialogInput=Color3.fromRGB(55,55,55),DialogInputLine=Color3.fromRGB(160,160,160),Text=Color3.fromRGB(240,240,240),SubText=Color3.fromRGB(170,170,170),Hover=Color3.fromRGB(120,120,120),HoverChange=0.07}end,[51]=function()local aa,ab,ac,ad,ae=b(51)return{Name='Darker',Accent=Color3.fromRGB(72,138,182),AcrylicMain=Color3.fromRGB(30,30,30),AcrylicBorder=Color3.fromRGB(60,60,60),AcrylicGradient=ColorSequence.new(Color3.fromRGB(25,25,25),Color3.fromRGB(15,15,15)),AcrylicNoise=0.94,TitleBarLine=Color3.fromRGB(65,65,65),Tab=Color3.fromRGB(100,100,100),Element=Color3.fromRGB(70,70,70),ElementBorder=Color3.fromRGB(25,25,25),InElementBorder=Color3.fromRGB(55,55,55),ElementTransparency=0.82,DropdownFrame=Color3.fromRGB(120,120,120),DropdownHolder=Color3.fromRGB(35,35,35),DropdownBorder=Color3.fromRGB(25,25,25),Dialog=Color3.fromRGB(35,35,35),DialogHolder=Color3.fromRGB(25,25,25),DialogHolderLine=Color3.fromRGB(20,20,20),DialogButton=Color3.fromRGB(35,35,35),DialogButtonBorder=Color3.fromRGB(55,55,55),DialogBorder=Color3.fromRGB(50,50,50),DialogInput=Color3.fromRGB(45,45,45),DialogInputLine=Color3.fromRGB(120,120,120)}end,[52]=function()local aa,ab,ac,ad,ae=b(52)return{Name='Light',Accent=Color3.fromRGB(0,103,192),AcrylicMain=Color3.fromRGB(200,200,200),AcrylicBorder=Color3.fromRGB(120,120,120),AcrylicGradient=ColorSequence.new(Color3.fromRGB(255,255,255),Color3.fromRGB(255,255,255)),AcrylicNoise=0.96,TitleBarLine=Color3.fromRGB(160,160,160),Tab=Color3.fromRGB(90,90,90),Element=Color3.fromRGB(255,255,255),ElementBorder=Color3.fromRGB(180,180,180),InElementBorder=Color3.fromRGB(150,150,150),ElementTransparency=0.65,ToggleSlider=Color3.fromRGB(40,40,40),ToggleToggled=Color3.fromRGB(255,255,255),SliderRail=Color3.fromRGB(40,40,40),DropdownFrame=Color3.fromRGB(200,200,200),DropdownHolder=Color3.fromRGB(240,240,240),DropdownBorder=Color3.fromRGB(200,200,200),DropdownOption=Color3.fromRGB(150,150,150),Keybind=Color3.fromRGB(120,120,120),Input=Color3.fromRGB(200,200,200),InputFocused=Color3.fromRGB(100,100,100),InputIndicator=Color3.fromRGB(80,80,80),Dialog=Color3.fromRGB(255,255,255),DialogHolder=Color3.fromRGB(240,240,240),DialogHolderLine=Color3.fromRGB(228,228,228),DialogButton=Color3.fromRGB(255,255,255),DialogButtonBorder=Color3.fromRGB(190,190,190),DialogBorder=Color3.fromRGB(140,140,140),DialogInput=Color3.fromRGB(250,250,250),DialogInputLine=Color3.fromRGB(160,160,160),Text=Color3.fromRGB(0,0,0),SubText=Color3.fromRGB(40,40,40),Hover=Color3.fromRGB(50,50,50),HoverChange=0.16}end,[53]=function()local aa,ab,ac,ad,ae=b(53)return{Name='Rose',Accent=Color3.fromRGB(180,55,90),AcrylicMain=Color3.fromRGB(40,40,40),AcrylicBorder=Color3.fromRGB(130,90,110),AcrylicGradient=ColorSequence.new(Color3.fromRGB(190,60,135),Color3.fromRGB(165,50,70)),AcrylicNoise=0.92,TitleBarLine=Color3.fromRGB(140,85,105),Tab=Color3.fromRGB(180,140,160),Element=Color3.fromRGB(200,120,170),ElementBorder=Color3.fromRGB(110,70,85),InElementBorder=Color3.fromRGB(120,90,90),ElementTransparency=0.86,ToggleSlider=Color3.fromRGB(200,120,170),ToggleToggled=Color3.fromRGB(0,0,0),SliderRail=Color3.fromRGB(200,120,170),DropdownFrame=Color3.fromRGB(200,160,180),DropdownHolder=Color3.fromRGB(120,50,75),DropdownBorder=Color3.fromRGB(90,40,55),DropdownOption=Color3.fromRGB(200,120,170),Keybind=Color3.fromRGB(200,120,170),Input=Color3.fromRGB(200,120,170),InputFocused=Color3.fromRGB(20,10,30),InputIndicator=Color3.fromRGB(170,150,190),Dialog=Color3.fromRGB(120,50,75),DialogHolder=Color3.fromRGB(95,40,60),DialogHolderLine=Color3.fromRGB(90,35,55),DialogButton=Color3.fromRGB(120,50,75),DialogButtonBorder=Color3.fromRGB(155,90,115),DialogBorder=Color3.fromRGB(100,70,90),DialogInput=Color3.fromRGB(135,55,80),DialogInputLine=Color3.fromRGB(190,160,180),Text=Color3.fromRGB(240,240,240),SubText=Color3.fromRGB(170,170,170),Hover=Color3.fromRGB(200,120,170),HoverChange=0.04}end}do local ab,ac,ad,ae,af,ag,ah,aj,c,e,f,g,h,i,j,k=task,setmetatable,error,newproxy,getmetatable,next,table,unpack,coroutine,script,type,require,pcall,getfenv,setfenv,rawget local l,m,n,o,p,s,t,u,v,w,x=ah.insert,ah.remove,ah.freeze or function(l)return l end,ab and ab.defer or function(l,...)local m=c.create(l)c.resume(m,...)return m end,'0.0.0-venv',{},{},{},{},{},{}local y,z={GetChildren=function(y)local z,A=x[y],{}for B in ag,z do l(A,B)end return A end,FindFirstChild=function(y,z)if not z then ad('Argument 1 missing or nil',2)end for A in ag,x[y]do if A.Name==z then return A end end return end,GetFullName=function(y)local z,A=y.Name,y.Parent while A do z=A.Name..'.'..z A=A.Parent end return'VirtualEnv.'..z end},{}for A,B in ag,y do z[A]=function(C,...)if not x[C]then ad("Expected ':' not '.' calling member function "..A,1)end return B(C,...)end end local C=function(C,D,E)local F,G,H,I,J=ac({},{__mode='k'}),function(F)ad(F..' is not a valid (virtual) member of '..C..' "'..D..'"',1)end,function(F)ad('Unable to assign (virtual) property '..F..'. Property is read only',1)end,(ae(true))local K=af(I)K.__index=function(L,M)if M=='ClassName'then return C elseif M=='Name'then return D elseif M=='Parent'then return E elseif C=='StringValue'and M=='Value'then return J else local N=z[M]if N then return N end end for N in ag,F do if N.Name==M then return N end end G(M)end K.__newindex=function(L,M,N)if M=='ClassName'then H(M)elseif M=='Name'then D=N elseif M=='Parent'then if N==I then return end if E~=nil then x[E][I]=nil end E=N if N~=nil then x[N][I]=true end elseif C=='StringValue'and M=='Value'then J=N else G(M)end end K.__tostring=function()return D end x[I]=F if E~=nil then x[E][I]=true end return I end local function D(E,F)local G,H,I,J=E[1],E[2],E[3],E[4]local K=m(I,1)local L=C(H,K,F)s[G]=L if I then for M,N in ag,I do L[M]=N end end if J then for M,N in ag,J do D(N,L)end end return L end local E={}for F,G in ag,a do l(E,D(G))end for H,I in ag,aa do local J=s[H]t[J]=I local K=J.ClassName if K=='LocalScript'or K=='Script'then l(v,J)end end local J=function(J)local K,L=J.ClassName,u[J]if L and K=='ModuleScript'then return aj(L)end local M=t[J]if not M then return end if K=='LocalScript'or K=='Script'then M()return else local N={M()}u[J]=N return aj(N)end end function b(K)local L=s[K]local M=t[L]if not M then return end local N,O,P,Q,R,S,T=false,n{Version=p,Script=e,Shared=w,GetScript=function()return e end,GetShared=function()return w end},L,function(N,...)if x[N]and N.ClassName=='ModuleScript'and t[N]then return J(N)end return g(N,...)end local U,V=function(U,...)if not N then T()end if f(U)=='number'and U>=0 then if U==0 then return S else U=U+1 local V,W=h(i,U)if V and W==R then return S end end end return i(U,...)end,function(U,V,...)if not N then T()end if f(U)=='number'and U>=0 then if U==0 then return j(S,V)else U=U+1 local W,X=h(i,U)if W and X==R then return j(S,V)end end end return j(U,V,...)end function T()R=i(0)local W={maui=O,script=P,require=Q,getfenv=U,setfenv=V}S=ac({},{__index=function(X,Y)local Z=k(S,Y)if Z~=nil then return Z end local _=W[Y]if _~=nil then return _ end return R[Y]end})j(M,S)N=true end return O,P,Q,U,V end for K,L in ag,v do o(J,L)end do local M for N,O in ag,E do if O.ClassName=='ModuleScript'and O.Name=='MainModule'then M=O break end end if M then return J(M)end end end

]]

local InterfaceManagerLocal = [[

local httpService = game:GetService("HttpService") -- Http

local InterfaceManager = {} do
	InterfaceManager.Folder = "FluentSettings"
    InterfaceManager.Settings = {
        Theme = "Dark",
        Acrylic = false,
        Transparency = true,
        MenuKeybind = "LeftControl"
    }

    function InterfaceManager:SetFolder(folder)
		self.Folder = folder;
		self:BuildFolderTree()
	end

    function InterfaceManager:SetLibrary(library)
		self.Library = library
	end

    function InterfaceManager:BuildFolderTree()
		local paths = {}

		local parts = self.Folder:split("/")
		for idx = 1, #parts do
			paths[#paths + 1] = table.concat(parts, "/", 1, idx)
		end

		table.insert(paths, self.Folder)
		table.insert(paths, self.Folder .. "/settings")

		for i = 1, #paths do
			local str = paths[i]
			if not isfolder(str) then
				makefolder(str)
			end
		end
	end

    function InterfaceManager:SaveSettings()
        writefile(self.Folder .. "/options.json", httpService:JSONEncode(InterfaceManager.Settings))
    end

    function InterfaceManager:LoadSettings()
        local path = self.Folder .. "/options.json"
        if isfile(path) then
            local data = readfile(path)
            local success, decoded = pcall(httpService.JSONDecode, httpService, data)

            if success then
                for i, v in next, decoded do
                    InterfaceManager.Settings[i] = v
                end
            end
        end
    end

    function InterfaceManager:BuildInterfaceSection(tab)
        assert(self.Library, "Must set InterfaceManager.Library")
		local Library = self.Library
        local Settings = InterfaceManager.Settings

        InterfaceManager:LoadSettings()

		local section = tab:AddSection("Interface")

		local InterfaceTheme = section:AddDropdown("InterfaceTheme", {
			Title = "Theme",
			Description = "Changes the interface theme.",
			Values = Library.Themes,
			Default = Settings.Theme,
			Callback = function(Value)
				Library:SetTheme(Value)
                Settings.Theme = Value
                InterfaceManager:SaveSettings()
			end
		})

        InterfaceTheme:SetValue(Settings.Theme)
	
		if Library.UseAcrylic then
			section:AddToggle("AcrylicToggle", {
				Title = "Acrylic",
				Description = "The blurred background requires graphic quality 8+",
				Default = Settings.Acrylic,
				Callback = function(Value)
					Library:ToggleAcrylic(Value)
                    Settings.Acrylic = Value
                    InterfaceManager:SaveSettings()
				end
			})
		end
	
		section:AddToggle("TransparentToggle", {
			Title = "Transparency",
			Description = "Makes the interface transparent.",
			Default = Settings.Transparency,
			Callback = function(Value)
				Library:ToggleTransparency(Value)
				Settings.Transparency = Value
                InterfaceManager:SaveSettings()
			end
		})
	
		local MenuKeybind = section:AddKeybind("MenuKeybind", { Title = "Minimize Bind", Default = Settings.MenuKeybind })
		MenuKeybind:OnChanged(function()
			Settings.MenuKeybind = MenuKeybind.Value
            InterfaceManager:SaveSettings()
		end)
		Library.MinimizeKeybind = MenuKeybind
    end
end

return InterfaceManager

]]

local SaveManagerLocal = [[

local httpService = game:GetService("HttpService")

print("Loading: SaveManager.lua");

local SaveManager = {} do
	SaveManager.Folder = "FluentSettings"
	SaveManager.Ignore = {}
	SaveManager.Parser = {
		Toggle = {
			Save = function(idx, object) 
				return { type = "Toggle", idx = idx, value = object.Value } 
			end,
			Load = function(idx, data)
				if SaveManager.Options[idx] then 
					SaveManager.Options[idx]:SetValue(data.value)
				end
			end,
		},
		Slider = {
			Save = function(idx, object)
				return { type = "Slider", idx = idx, value = tostring(object.Value) }
			end,
			Load = function(idx, data)
				if SaveManager.Options[idx] then 
					SaveManager.Options[idx]:SetValue(data.value)
				end
			end,
		},
		Dropdown = {
			Save = function(idx, object)
				return { type = "Dropdown", idx = idx, value = object.Value, mutli = object.Multi }
			end,
			Load = function(idx, data)
				if SaveManager.Options[idx] then 
					SaveManager.Options[idx]:SetValue(data.value)
				end
			end,
		},
		Colorpicker = {
			Save = function(idx, object)
				return { type = "Colorpicker", idx = idx, value = object.Value:ToHex(), transparency = object.Transparency }
			end,
			Load = function(idx, data)
				if SaveManager.Options[idx] then 
					SaveManager.Options[idx]:SetValueRGB(Color3.fromHex(data.value), data.transparency)
				end
			end,
		},
		Keybind = {
			Save = function(idx, object)
				return { type = "Keybind", idx = idx, mode = object.Mode, key = object.Value }
			end,
			Load = function(idx, data)
				if SaveManager.Options[idx] then 
					SaveManager.Options[idx]:SetValue(data.key, data.mode)
				end
			end,
		},

		Input = {
			Save = function(idx, object)
				return { type = "Input", idx = idx, text = object.Value }
			end,
			Load = function(idx, data)
				if SaveManager.Options[idx] and type(data.text) == "string" then
					SaveManager.Options[idx]:SetValue(data.text)
				end
			end,
		},
	}

	function SaveManager:SetIgnoreIndexes(list)
		for _, key in next, list do
			self.Ignore[key] = true
		end
	end

	function SaveManager:SetFolder(folder)
		self.Folder = folder;
		self:BuildFolderTree()
	end

	function SaveManager:Save(name)
		if (not name) then
			return false, "no config file is selected"
		end

		local fullPath = self.Folder .. "/settings/" .. name .. ".json"

		local data = {
			objects = {}
		}

		for idx, option in next, SaveManager.Options do
			if not self.Parser[option.Type] then continue end
			if self.Ignore[idx] then continue end

			table.insert(data.objects, self.Parser[option.Type].Save(idx, option))
		end	

		local success, encoded = pcall(httpService.JSONEncode, httpService, data)
		if not success then
			return false, "failed to encode data"
		end

		writefile(fullPath, encoded)
		return true
	end

	function SaveManager:Load(name)
		if (not name) then
			return false, "no config file is selected"
		end
		
		local file = self.Folder .. "/settings/" .. name .. ".json"
		if not isfile(file) then return false, "invalid file" end

		local success, decoded = pcall(httpService.JSONDecode, httpService, readfile(file))
		if not success then return false, "decode error" end

		for _, option in next, decoded.objects do
			if self.Parser[option.type] then
				task.spawn(function() self.Parser[option.type].Load(option.idx, option) end) -- task.spawn() so the config loading wont get stuck.
			end
		end

		return true
	end

	function SaveManager:IgnoreThemeSettings()
		self:SetIgnoreIndexes({ 
			"InterfaceTheme", "AcrylicToggle", "TransparentToggle", "MenuKeybind"
		})
	end

	function SaveManager:BuildFolderTree()
		local paths = {
			self.Folder,
			self.Folder .. "/settings"
		}

		for i = 1, #paths do
			local str = paths[i]
			if not isfolder(str) then
				makefolder(str)
			end
		end
	end

	function SaveManager:RefreshConfigList()
		local list = listfiles(self.Folder .. "/settings")

		local out = {}
		for i = 1, #list do
			local file = list[i]
			if file:sub(-5) == ".json" then
				local pos = file:find(".json", 1, true)
				local start = pos

				local char = file:sub(pos, pos)
				while char ~= "/" and char ~= "\\" and char ~= "" do
					pos = pos - 1
					char = file:sub(pos, pos)
				end

				if char == "/" or char == "\\" then
					local name = file:sub(pos + 1, start - 1)
					if name ~= "options" then
						table.insert(out, name)
					end
				end
			end
		end
		
		return out
	end

	function SaveManager:SetLibrary(library)
		self.Library = library
        self.Options = library.Options
	end

	function SaveManager:LoadAutoloadConfig()
		if isfile(self.Folder .. "/settings/autoload.txt") then
			local name = readfile(self.Folder .. "/settings/autoload.txt")

			local success, err = self:Load(name)
			if not success then
				return self.Library:Notify({
					Title = "Interface",
					Content = "Config loader",
					SubContent = "Failed to load autoload config: " .. err,
					Duration = 7
				})
			end

			self.Library:Notify({
				Title = "Interface",
				Content = "Config loader",
				SubContent = string.format("Auto loaded config %q", name),
				Duration = 7
			})
		end
	end

	function SaveManager:BuildConfigSection(tab)
		assert(self.Library, "Must set SaveManager.Library")

		local section = tab:AddSection("Configuration")

		section:AddInput("SaveManager_ConfigName",    { Title = "Config name" })
		section:AddDropdown("SaveManager_ConfigList", { Title = "Config list", Values = self:RefreshConfigList(), AllowNull = true })

		section:AddButton({
            Title = "Create config",
            Callback = function()
                local name = SaveManager.Options.SaveManager_ConfigName.Value

                if name:gsub(" ", "") == "" then 
                    return self.Library:Notify({
						Title = "Interface",
						Content = "Config loader",
						SubContent = "Invalid config name (empty)",
						Duration = 7
					})
                end

                local success, err = self:Save(name)
                if not success then
                    return self.Library:Notify({
						Title = "Interface",
						Content = "Config loader",
						SubContent = "Failed to save config: " .. err,
						Duration = 7
					})
                end

				self.Library:Notify({
					Title = "Interface",
					Content = "Config loader",
					SubContent = string.format("Created config %q", name),
					Duration = 7
				})

                SaveManager.Options.SaveManager_ConfigList:SetValues(self:RefreshConfigList())
                SaveManager.Options.SaveManager_ConfigList:SetValue(nil)
            end
        })

        section:AddButton({Title = "Load config", Callback = function()
			local name = SaveManager.Options.SaveManager_ConfigList.Value

			local success, err = self:Load(name)
			if not success then
				return self.Library:Notify({
					Title = "Interface",
					Content = "Config loader",
					SubContent = "Failed to load config: " .. err,
					Duration = 7
				})
			end

			self.Library:Notify({
				Title = "Interface",
				Content = "Config loader",
				SubContent = string.format("Loaded config %q", name),
				Duration = 7
			})
		end})

		section:AddButton({Title = "Overwrite config", Callback = function()
			local name = SaveManager.Options.SaveManager_ConfigList.Value

			local success, err = self:Save(name)
			if not success then
				return self.Library:Notify({
					Title = "Interface",
					Content = "Config loader",
					SubContent = "Failed to overwrite config: " .. err,
					Duration = 7
				})
			end

			self.Library:Notify({
				Title = "Interface",
				Content = "Config loader",
				SubContent = string.format("Overwrote config %q", name),
				Duration = 7
			})
		end})

		section:AddButton({Title = "Refresh list", Callback = function()
			SaveManager.Options.SaveManager_ConfigList:SetValues(self:RefreshConfigList())
			SaveManager.Options.SaveManager_ConfigList:SetValue(nil)
		end})

		local AutoloadButton
		AutoloadButton = section:AddButton({Title = "Set as autoload", Description = "Current autoload config: none", Callback = function()
			local name = SaveManager.Options.SaveManager_ConfigList.Value
			writefile(self.Folder .. "/settings/autoload.txt", name)
			AutoloadButton:SetDesc("Current autoload config: " .. name)
			self.Library:Notify({
				Title = "Interface",
				Content = "Config loader",
				SubContent = string.format("Set %q to auto load", name),
				Duration = 7
			})
		end})

		if isfile(self.Folder .. "/settings/autoload.txt") then
			local name = readfile(self.Folder .. "/settings/autoload.txt")
			AutoloadButton:SetDesc("Current autoload config: " .. name)
		end

		SaveManager:SetIgnoreIndexes({ "SaveManager_ConfigList", "SaveManager_ConfigName" })
	end

	SaveManager:BuildFolderTree()
end

return SaveManager

]]


local Fluent = loadstring(FluentLocal)()
local SaveManager = loadstring(SaveManagerLocal)()
local InterfaceManager = loadstring(InterfaceManagerLocal)()


function Remotes()
	DebugCheck(0,"HASH AUTO UPDATE 4")

	function UpdateRemote(RemoteName, Value)
		if game:FindFirstChild("_REMOTES_NEKO_") == nil then
			local REMOTES = Instance.new("Folder")
			REMOTES.Name = "_REMOTES_NEKO_"
			REMOTES.Parent = game
			UpdateRemote(RemoteName, Value)
		else
			if game:FindFirstChild("_REMOTES_NEKO_"):FindFirstChild(RemoteName) == nil then
				local _NEWREMOTE = Instance.new("StringValue")
				_NEWREMOTE.Name = RemoteName
				_NEWREMOTE.Value = Value
				_NEWREMOTE.Parent = game:FindFirstChild("_REMOTES_NEKO_")
			else
				DebugCheck(0,"Remote Update: "..RemoteName)
				game:FindFirstChild("_REMOTES_NEKO_"):FindFirstChild(RemoteName).Value = Value
			end
		end
	end

	if IsFolder("/Hash System") and IsFile("Game Version") and ReadFile("Game Version") and game.PlaceVersion == tonumber(ReadFile("Game Version")) then
		print("Ist Nicht geupdated!")

		UpdateRemote("KillRemote", ReadFile("/Hash System/KillRemote")) -- 2
		UpdateRemote("KillRemoteHashName", ReadFile("/Hash System/KillRemoteHashName")) -- 2
		_G.KillRemoteHash = ReadFile("/Hash System/KillRemoteHash")

		UpdateRemote("FishFarmFinishRemote", ReadFile("/Hash System/FishFarmFinishRemote")) -- 2
		UpdateRemote("AngelRemote", ReadFile("/Hash System/AngelRemote")) -- 2

		UpdateRemote("TOOL_PICKUPHashData", ReadFile("/Hash System/TOOL_PICKUPHashData")) -- 2
		_G.TOOL_PICKUPHash = ReadFile("/Hash System/TOOL_PICKUPHash")

		UpdateRemote("CropHashData", ReadFile("/Hash System/CropHashData")) -- 2
		_G.CropHash = ReadFile("/Hash System/CropHash")

		UpdateRemote("TreeHashData", ReadFile("/Hash System/TreeHashData")) -- 2
		_G.TreeHash = ReadFile("/Hash System/TreeHash")
		UpdateRemote("BlockHitHashData", ReadFile("/Hash System/BlockHitHashData")) -- 2
		_G.BlockHitHash = ReadFile("/Hash System/BlockHitHash")

		UpdateRemote("FlowerCollect", "client_request_1") -- 1
		UpdateRemote("PetCollect", "CLIENT_PET_ANIMAL")
		UpdateRemote("BlockRemote", "CLIENT_BLOCK_HIT_REQUEST")
		UpdateRemote("SpiritRemote", "nflutpppqsFS/ZroaqkcspgrTkvpnkrdWcc")

		UpdateRemote("CropPlaceHashData", ReadFile("/Hash System/CropPlaceHashData")) -- 2
		_G.CropPlaceHash = ReadFile("/Hash System/CropPlaceHash") -- 2
		_G.CropPlaceH1 = ReadFile("/Hash System/BlockPlaceHashData") 
		UpdateRemote("BlockPlaceHashData", ReadFile("/Hash System/BlockPlaceHashData")) -- 2
		_G.BlockPlaceHash = ReadFile("/Hash System/BlockPlaceHash") -- 2

	else

		CreateFolder("Hash System")

		print("Getting Hashes!")

		CreateFile("Game Version", tostring(game.PlaceVersion), false)

		function Update()
			local MOBRIGHT = ""
			local MOBLEFT = ""
			local mobRemoteName = ""
			function UpdateMob()

				local Tool

				for i,v in pairs(game:GetService("ReplicatedStorage").Tools:GetChildren()) do 
					if v.Name == "swordWood" then
						local Clone = v:Clone()
						Clone.Parent = game.Players.LocalPlayer.Character
						task.wait(0.2)
						Clone.Parent = game.Players.LocalPlayer.Backpack
						task.wait(0.2)
						Clone.Parent = game.Players.LocalPlayer.Character
						task.wait(0.2)
						Tool = Clone
					end
				end

				local function getrem(p9)
					rem = ""
					for i,v in pairs(game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"]["@rbxts"].net.out["_NetManaged"]:GetChildren()) do
						if v.Name:match(p9) then
							rem = v
						end
					end
					return rem.Name
				end
				local remleft = ""
				mobrem = ""
				for i,v in pairs(getgc(true)) do
					if type(v) == "function" and getinfo(v).name == "attemptHit" then
						for i2,v2 in pairs(getprotos(v)) do
							for i3,v3 in pairs(getprotos(v2)) do
								mobrem = getrem("/"..getconstants(v3)[1])
								remleft = getconstants(v3)[4]
							end
						end
					end
				end


				for i,v in pairs(getgc(true)) do
					if type(v) == "function" and getinfo(v).name == "attemptHit" then
						MOBRIGHT = getupvalues(v)[5]
						task.wait() -- 1
					end
				end
				print("mobrem:",mobrem)
				mobramsides = string.split(mobrem, "/")

				MOBLEFT = remleft
				if mobramsides and mobramsides[1] and mobramsides[2] then
					mobRemoteName = mobramsides[1].."/"..mobramsides[2]
					if MOBRIGHT then
						_G.KillRemoteHash = MOBRIGHT
					else
						_G.KillRemoteHash = nil
					end 
				else
					_G.KillRemoteHash = nil
					local RunService = game:GetService("RunService")
					local CoreGui = game:GetService("CoreGui")




				end
				if Tool then
					DebugCheck(0,"Sword ist da")

					Tool.Parent = game.Players.LocalPlayer.Backpack
					Tool:Destroy()
				else
					DebugCheck(0,"NO SWORD!")
				end
			end

			UpdateMob()


			local Remote1
			local Remote15
			local Remote2

			function UpdateFish()

				local Tool

				for i,v in pairs(game:GetService("ReplicatedStorage").Tools:GetChildren()) do 
					if v.Name == "fishingRod" then
						local Clone = v:Clone()
						Clone.Parent = game.Players.LocalPlayer.Character
						task.wait(0.5)
						Clone.Parent = game.Players.LocalPlayer.Backpack
						task.wait(0.5)
						Clone.Parent = game.Players.LocalPlayer.Character
						task.wait(0.5)
						Tool = Clone
					end
				end

				local function getrem(p9)
					rem = ""
					for i,v in pairs(game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"]["@rbxts"].net.out["_NetManaged"]:GetChildren()) do
						if v.Name:match(p9) then
							rem = v
						end
					end
					return rem.Name
				end

				local WerfRemote

				local dump1
				local dump2



				if Tool then
					local ToolScript = Tool:FindFirstChild("fishing-rod")

					if Tool and ToolScript then
						for i,v222 in pairs(getgc(true)) do
							if type(v222) == "function" and  getfenv(v222).script == ToolScript then


								for i,v in pairs(getconstants(v222)) do
									if i == 9 then

										if getrem(v) then
											DebugCheck(0,v)
											if v == 1.5 or v == "1.5" then

											else
												Remote1 = v
												Remote15 = string.split(Remote1, "/")[1]
												DebugCheck(0,"Remote15:",Remote15)

											end
										end
									end

									if i == 3 then
										if type(v) == "string" then
											if getrem(v) then

												Remote2 = v
												dump2 = Remote2
											end
										end
									end
								end

							end
						end

						local FinishRemote

						local function getrem(p9)
							rem = ""
							for i,v in pairs(game:GetService("ReplicatedStorage")["rbxts_include"]["node_modules"]["@rbxts"].net.out["_NetManaged"]:GetChildren()) do
								if v.Name:match(p9) then
									rem = v
								end
							end
							return rem.Name
						end

						for i,v222 in pairs(getgc(true)) do
							if type(v222) == "function" and getinfo(v222).name == "handleGameOver" and getfenv(v222).script == game:GetService("Players").LocalPlayer.PlayerScripts.TS.flame.controllers.fishing["fishing-controller"] then


								for i,v in pairs(getconstants(v222)) do

									if type(v) == "string" then

										if getrem(v) then
											if i == 2 then
												DebugCheck(0,"FINISH: ",v)
												dump1 = v
												DebugCheck(0,Remote15)
												WerfRemote = Remote2.."/"..Remote15
												DebugCheck(0,"FNISH2:",WerfRemote)
											end
										end

									end

								end

							end
						end
						--[[

								if FinishRemote then
									UpdateRemote("FishFarmFinishRemote", FinishRemote)
									DebugCheck(0,"FishFarmFinishRemote", FinishRemote)
								else
									game.Players.LocalPlayer:Kick("cant get FinishRemote!")
								end
								if FinishRemote then
									UpdateRemote("AngelRemote", Remote1)
									DebugCheck(0,"AngelRemote", Remote1)
								else
									game.Players.LocalPlayer:Kick("cant get AngelRemote!")
								end

						]]
					end
				end

				local Finishremote = dump2.."/"..dump1

				DebugCheck(0,"FinishRemote:",Finishremote)

				if WerfRemote then
					DebugCheck(0,"WerfRemote:",WerfRemote)
				end

				UpdateRemote("FishFarmFinishRemote", Finishremote) -- 2
				SendNotification("[SECURITY]", "Check 1/42 Done!")
				UpdateRemote("AngelRemote", WerfRemote) -- 2
				SendNotification("[SECURITY]", "Check 2/42 Done!")

				CreateFile("/Hash System/FishFarmFinishRemote", Finishremote, false)
				SendNotification("[SECURITY]", "Check 3/42 Done!")
				CreateFile("/Hash System/AngelRemote", WerfRemote, false)
				SendNotification("[SECURITY]", "Check 4/42 Done!")
				Tool.Parent = game.Players.LocalPlayer.Backpack
				Tool:Destroy()

			end



			-- UpdateFish()

			task.spawn(function()
				UpdateFish()
				task.wait()
			end)

			function Updateinv(v)
				if v:FindFirstChild("sword") then
					if _G.KillRemoteHash == nil or _G.KillRemoteHash == "" or _G.KillRemoteHash == " " then
						UpdateMob()
						task.wait()
						UpdateRemote("KillRemote", mobRemoteName) -- 2
						SendNotification("[SECURITY]", "Check 5/42 Done!")
						UpdateRemote("KillRemoteHashName", MOBLEFT) -- 2
						SendNotification("[SECURITY]", "Check 6/42 Done!")
						_G.KillRemoteHash = MOBRIGHT
						SendNotification("[SECURITY]", "Check 7/42 Done!")
					end
				end
			end

			game.Players.LocalPlayer.Backpack.ChildAdded:Connect(function(v)
				Updateinv(v)
			end)

			game.Players.LocalPlayer.Backpack.ChildRemoved:Connect(function(v)
				Updateinv(v)
			end)

			print("mobRemoteName:",mobRemoteName)

			UpdateRemote("KillRemote", mobRemoteName) -- 2
			SendNotification("[SECURITY]", "Check 8/42 Done!")
			UpdateRemote("KillRemoteHashName", MOBLEFT) -- 2
			SendNotification("[SECURITY]", "Check 9/42 Done!")
			_G.KillRemoteHash = MOBRIGHT

			print("Debug 1")

			task.wait()

			CreateFile("/Hash System/KillRemote", mobRemoteName, false)
			SendNotification("[SECURITY]", "Check 10/42 Done!")
			CreateFile("/Hash System/KillRemoteHashName", MOBLEFT, false)
			SendNotification("[SECURITY]", "Check 11/42 Done!")
			CreateFile("/Hash System/KillRemoteHash", MOBRIGHT or _G.KillRemoteHash, false)
			SendNotification("[SECURITY]", "Check 12/42 Done!")

			print("Debug 2")


			local ToolLEFT
			local TOOLRIGHT 
			function UpdatePickUpTool()
				for i,v in pairs(getgc(true)) do
					if type(v) == "function" and getinfo(v).name == "pickupTool" then
						ToolLEFT = getconstants(v)[23]
						TOOLRIGHT = getconstants(v)[25]..getconstants(v)[26]
					end
				end
			end
			task.spawn(function()
				UpdatePickUpTool()
			end)

			print("Debug 3")

			UpdateRemote("TOOL_PICKUPHashData", ToolLEFT) -- 2
			SendNotification("[SECURITY]", "Check 13/42 Done!")
			_G.TOOL_PICKUPHash = TOOLRIGHT
			SendNotification("[SECURITY]", "Check 14/42 Done!")

			CreateFile("/Hash System/TOOL_PICKUPHashData", ToolLEFT, false)
			SendNotification("[SECURITY]", "Check 15/42 Done!")
			CreateFile("/Hash System/TOOL_PICKUPHash", TOOLRIGHT, false)
			SendNotification("[SECURITY]", "Check 16/42 Done!")

			print("Debug 4")

			local CROPleft
			local CROPright
			function CropUpdate()
				remleft = ""
				remright = ""
				for i,v in pairs(getgc(true)) do
					if type(v) == "function" and getinfo(v).name == "breakCrop" and getfenv(v).script == game.Players.LocalPlayer.PlayerScripts.TS.block.crop["crop-service"] then
						for i2,v2 in pairs(getprotos(v)) do

							for i,v in pairs(getconstants(v)) do

								if i == 22 then
									remleft = v 
								end 

								if i == 26 then
									remright = v 
								end


								if i == 27 then
									remright = remright..v
								end


							end
						end
					end
				end    
				if remleft and remright then
					CROPleft = remleft
					CROPright = remright
				else
					game.Players.LocalPlayer:Kick("Error: NCD1")
				end
			end
			task.spawn(function()
				CropUpdate()
			end)

			print("Debug 5")

			local HITleft
			local HITright
			function HitUpdate()
				remright2 = ""
				remleft = ""
				remright = ""
				for i,v in pairs(getgc(true)) do
					if type(v) == "function" and getinfo(v).name == "onBlockHit" then
						for i2,v2 in pairs(getprotos(v)) do
							if table.find(getconstants(v2), "Get") then
								for i3,v3 in pairs(getconstants(v2)) do
									remleft = getconstants(v2)[8]
									remright2 = getconstants(v2)[11]
									remright = getconstants(v2)[10]
								end
							end
						end
					end
				end

				HITleft = remleft
				HITright = remright..remright2
			end
			task.spawn(function()
				HitUpdate()
			end)

			task.wait(0.2)

			print("Debug 6")

			UpdateRemote("CropHashData", CROPleft) -- 2
			SendNotification("[SECURITY]", "Check 17/42 Done!")
			_G.CropHash = CROPright
			SendNotification("[SECURITY]", "Check 18/42 Done!")


			UpdateRemote("TreeHashData", HITleft) -- 2
			SendNotification("[SECURITY]", "Check 19/42 Done!")
			_G.TreeHash = HITright
			SendNotification("[SECURITY]", "Check 20/42 Done!")
			UpdateRemote("BlockHitHashData", HITleft) -- 2
			SendNotification("[SECURITY]", "Check 21/42 Done!")
			_G.BlockHitHash = HITright
			SendNotification("[SECURITY]", "Check 22/42 Done!")

			CreateFile("/Hash System/CropHashData", CROPleft, false)
			SendNotification("[SECURITY]", "Check 23/42 Done!")
			CreateFile("/Hash System/CropHash", CROPright, false)
			SendNotification("[SECURITY]", "Check 24/42 Done!")

			print("Debug 7")

			CreateFile("/Hash System/TreeHashData", HITleft, false)
			SendNotification("[SECURITY]", "Check 25/42 Done!")
			CreateFile("/Hash System/TreeHash", HITright, false)
			SendNotification("[SECURITY]", "Check 26/42 Done!")
			CreateFile("/Hash System/BlockHitHashData", HITleft, false)
			SendNotification("[SECURITY]", "Check 27/42 Done!")
			CreateFile("/Hash System/BlockHitHash", HITright, false)
			SendNotification("[SECURITY]", "Check 28/42 Done!")

			print("Debug 8")


			local BlockRight1
			local BlockRight
			local BlockLeft
			function UpdatePlaceBlocks()


				for i,v in pairs(getgc(true)) do
					if type(v) == "function" and getfenv(v).script == game.Players.LocalPlayer.PlayerScripts.TS.flame.controllers.block["block-controller"] then

						for dddi,dddv in pairs(getconstants(v)) do

							if tonumber(dddi) == 23 then
								BlockLeft = dddv
							end
							if tonumber(dddi) == 25 then
								BlockLeft1 = dddv
							end
							if tonumber(dddi) == 26 then
								BlockRight = BlockLeft1..dddv
							end
						end
					end
				end

			end
			UpdatePlaceBlocks()

			print("Debug 9")

			function GetNet()
				local A1
				local A2

				for i,v in pairs(getgc(true)) do
					if type(v) == "function" and getinfo(v).name == "constructor" and getfenv(v).script == game:GetService("Workspace").ANTICATBYASHO.net.net then

						for i2,v2 in pairs(getprotos(v)) do

							A1 = getconstants(v2)[16]

							A2 = getconstants(v2)[13]

							for i,v in pairs(getconstants(v2)) do
								DebugCheck(0,i,v, " | type:", type(v)) 
							end


						end
					end
				end

				DebugCheck(0,A1)
				DebugCheck(0,A2)
			end

			print("Debug 10")

			UpdateRemote("FlowerCollect", "client_request_1") -- 1
			SendNotification("[SECURITY]", "Check 29/42 Done!")
			UpdateRemote("PetCollect", "CLIENT_PET_ANIMAL")
			SendNotification("[SECURITY]", "Check 30/42 Done!")
			UpdateRemote("BlockRemote", "CLIENT_BLOCK_HIT_REQUEST")
			SendNotification("[SECURITY]", "Check 31/42 Done!")
			-- UpdateRemote("SendMailRemote", "NINGI(HUINUH(UIN(IH(HUUI")
			SendNotification("[SECURITY]", "Check 32/42 Done!")
			UpdateRemote("SpiritRemote", "gecqaLhbvAbyjo/qDgqEvuQzyryuBnlzh")
			SendNotification("[SECURITY]", "Check 33/42 Done!")

			print("BlockLeft:",BlockLeft)

			UpdateRemote("CropPlaceHashData", BlockLeft) -- 2
			SendNotification("[SECURITY]", "Check 34/42 Done!")
			_G.CropPlaceHash = BlockRight -- 2
			SendNotification("[SECURITY]", "Check 35/42 Done!")
			_G.CropPlaceH1 = BlockLeft
			SendNotification("[SECURITY]", "Check 36/42 Done!")
			UpdateRemote("BlockPlaceHashData", BlockLeft) -- 2
			SendNotification("[SECURITY]", "Check 37/42 Done!")
			_G.BlockPlaceHash = BlockRight -- 2
			SendNotification("[SECURITY]", "Check 38/42 Done!")

			print("Debug 11")

			CreateFile("/Hash System/CropPlaceHashData", BlockLeft, false)
			SendNotification("[SECURITY]", "Check 39/42 Done!")
			CreateFile("/Hash System/CropPlaceHash", BlockRight, false)
			SendNotification("[SECURITY]", "Check 40/42 Done!")
			CreateFile("/Hash System/BlockPlaceHashData", BlockLeft, false)
			SendNotification("[SECURITY]", "Check 41/42 Done!")
			CreateFile("/Hash System/BlockPlaceHash", BlockRight, false)
			SendNotification("[SECURITY]", "Check 42/42 Done!")
		end
		Update()
	end
end

SendNotification("[SECURITY]", "Scanning Game...")

Remotes()

function FixInv()
	for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		v.Parent = game.Players.LocalPlayer.Character
		task.wait()
		v.Parent = game.Players.LocalPlayer.Backpack
		task.wait()
	end
end

local RemoteData = game:WaitForChild("_REMOTES_NEKO_")


_G.Island_USERID = game.Players.LocalPlayer.UserId

local CANUSEAUTOCLICKER = true



local MotHitH1 = RemoteData:FindFirstChild("KillRemoteHashName").Value
local MotHitH2 = _G.KillRemoteHash 

local CropPlaceH1 = RemoteData:FindFirstChild("CropPlaceHashData").Value
local CropPlaceH2 = _G.CropPlaceHash

local PickupH1 = RemoteData:FindFirstChild("TOOL_PICKUPHashData").Value
local PickupH2 = _G.TOOL_PICKUPHash

local PlaceHASHName = RemoteData:FindFirstChild("BlockPlaceHashData").Value
local PlaceHASH = _G.BlockPlaceHash

local HitHASHName = RemoteData:FindFirstChild("BlockHitHashData").Value
local HitHASH = _G.BlockHitHash


local MAINSCRIPTHANDLER

local LASTTWEEN = nil

-- CROP TEST --

local SichleAuraCooldown = false 
local SichleFarmCooldown = false
local CROPTWEEN22


-- Tables --
local SettingsTable = {

	-- Tween Fly -- 

	Twennnoclip = true,
	TweenFly = true,
	TweenFast = true,

	-- Player --

	PlayerFly = false,

	-- Script --

	AutoUpdate = true

}

local UserSettings = {

	TeleportMethod = "Tween" -- or Instant


}

local MaxCropDis = 30




local FloatRender
local FloatPart
local UseFloat = false

local Float_Part = Instance.new('Part')
Float_Part.Name = "floatName"
Float_Part.Parent = game.Players.LocalPlayer.Character
Float_Part.Transparency = 1
Float_Part.Size = Vector3.new(2,0.2,1.5)
Float_Part.Anchored = true
FloatPart = Float_Part
FloatRender = game:GetService("RunService").RenderStepped:Connect(function()
	if UseFloat == true then
		Float_Part.CanCollide = true
		Float_Part.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-3.1,0) 
	else
		Float_Part.CanCollide = false
	end
end)

function MiniTpBlocks(Model,position)

	if Model then
		for i,v in pairs(Model:GetDescendants()) do
			if v:IsA("Part") or v:IsA("BasePart") then
				v.CanCollide = false
			end
		end
	end

	local function MiniTpV2(position)

		Model:SetPrimaryPartCFrame(CFrame.new(position))

	end

	local myPart = Model.PrimaryPart
	local targetPosition = position
	local minDistance = 3 -- Minimum distance to target to trigger teleport
	local maxIterations = 3 -- Maximum number of iterations to allow with no progress

	DebugCheck(0,"Initial Position: " .. tostring(myPart.Position))
	DebugCheck(0,"Target Position: " .. tostring(targetPosition))

	local prevDistance = (myPart.Position - targetPosition).magnitude
	local noProgressCount = 0
	while (myPart.Position - targetPosition).magnitude > minDistance do
		local offset = targetPosition - myPart.Position
		local distance = offset.Magnitude

		local step
		local waitTime
		step = Vector3.new(3, 3, 3)
		waitTime = 0

		local direction = offset.Unit
		local steps = math.ceil(distance / step.Magnitude)
		local newStep = offset / steps

		local progress = false
		for i = 1, steps do
			local newPos = myPart.Position + newStep * i
			if newPos.X > targetPosition.X and newStep.X > 0 then
				newStep = Vector3.new(0, newStep.Y, newStep.Z)
			elseif newPos.X < targetPosition.X and newStep.X < 0 then 
				newStep = Vector3.new(0, newStep.Y, newStep.Z) 
			end 
			if newPos.Y > targetPosition.Y and newStep.Y > 0 then 
				newStep = Vector3.new(newStep.X, 0, newStep.Z) 
			elseif newPos.Y < targetPosition.Y and newStep.Y < 0 then 
				newStep = Vector3.new(newStep.X, 0, newStep.Z) 
			end 
			if newPos.Z > targetPosition.Z and newStep.Z > 0 then 
				newStep = Vector3.new(newStep.X, newStep.Y, 0) 
			elseif newPos.Z < targetPosition.Z and newStep.Z < 0 then 
				newStep = Vector3.new(newStep.X, newStep.Y, 0) 
			end 
			newPos = myPart.Position + newStep
			MiniTpV2(newPos)
			DebugCheck(0,"Current Position: " .. tostring(myPart.Position))
			DebugCheck(0,"In radius!") -- Ausgabe, wenn der Spieler innerhalb des Radius ist
			wait(waitTime)
			local currDistance = (myPart.Position - targetPosition).magnitude
			if currDistance >= prevDistance then
				noProgressCount = noProgressCount + 1
			else
				prevDistance = currDistance
				noProgressCount = 0
				progress = true
			end
			if noProgressCount >= maxIterations then
				DebugCheck(0,"Stuck! Breaking out of loop...")
				break
			end
		end
		if not progress then
			DebugCheck(0,"Stuck! Breaking out of loop...")
			break
		end
	end

	--[[

		-- Teleport to target position if close enough
	if (myPart.Position - targetPosition).magnitude <= minDistance then
		MiniTpV2(targetPosition)
	end

	DebugCheck(0,"Final Position: " .. tostring(myPart.Position))
	DebugCheck(0,"Reached Target Position!")
	FloatRender:Disconnect()
	FloatPart:Destroy()

	]]
end


function MiniTp(position)
	UseFloat = true
	local function MiniTpV2(position)
		local player = game:GetService("Players").LocalPlayer
		local character = player.Character
		if character and character.PrimaryPart then
			character:SetPrimaryPartCFrame(CFrame.new(position))
		end
	end

	local myPart = game.Players.LocalPlayer.Character.HumanoidRootPart
	local targetPosition = position
	local minDistance = 3 -- Minimum distance to target to trigger teleport
	local maxIterations = 3 -- Maximum number of iterations to allow with no progress

	DebugCheck(0,"Initial Position: " .. tostring(myPart.Position))
	DebugCheck(0,"Target Position: " .. tostring(targetPosition))

	local prevDistance = (myPart.Position - targetPosition).magnitude
	local noProgressCount = 0
	while (myPart.Position - targetPosition).magnitude > minDistance do
		local offset = targetPosition - myPart.Position
		local distance = offset.Magnitude

		local step
		local waitTime
		if distance <= 50 then
			step = Vector3.new(1, 2, 1)
			waitTime = 0.04
		elseif distance <= 30 then
			step = Vector3.new(1, 2, 1)
			waitTime = 0.005
		else
			step = Vector3.new(2.5, 4.5, 2.5)
			waitTime = 0.20
		end

		local direction = offset.Unit
		local steps = math.ceil(distance / step.Magnitude)
		local newStep = offset / steps

		local progress = false
		for i = 1, steps do
			local newPos = myPart.Position + newStep * i
			if newPos.X > targetPosition.X and newStep.X > 0 then
				newStep = Vector3.new(0, newStep.Y, newStep.Z)
			elseif newPos.X < targetPosition.X and newStep.X < 0 then 
				newStep = Vector3.new(0, newStep.Y, newStep.Z) 
			end 
			if newPos.Y > targetPosition.Y and newStep.Y > 0 then 
				newStep = Vector3.new(newStep.X, 0, newStep.Z) 
			elseif newPos.Y < targetPosition.Y and newStep.Y < 0 then 
				newStep = Vector3.new(newStep.X, 0, newStep.Z) 
			end 
			if newPos.Z > targetPosition.Z and newStep.Z > 0 then 
				newStep = Vector3.new(newStep.X, newStep.Y, 0) 
			elseif newPos.Z < targetPosition.Z and newStep.Z < 0 then 
				newStep = Vector3.new(newStep.X, newStep.Y, 0) 
			end 
			newPos = myPart.Position + newStep
			MiniTpV2(newPos)
			DebugCheck(0,"Current Position: " .. tostring(myPart.Position))
			DebugCheck(0,"In radius!") -- Ausgabe, wenn der Spieler innerhalb des Radius ist
			wait(waitTime)
			local currDistance = (myPart.Position - targetPosition).magnitude
			if currDistance >= prevDistance then
				noProgressCount = noProgressCount + 1
			else
				prevDistance = currDistance
				noProgressCount = 0
				progress = true
			end
			if noProgressCount >= maxIterations then
				DebugCheck(0,"Stuck! Breaking out of loop...")
				break
			end
		end
		if not progress then
			DebugCheck(0,"Stuck! Breaking out of loop...")
			break
		end
	end
	-- Teleport to target position if close enough
	if (myPart.Position - targetPosition).magnitude <= minDistance then
		MiniTpV2(targetPosition)
	end

	DebugCheck(0,"Final Position: " .. tostring(myPart.Position))
	DebugCheck(0,"Reached Target Position!")
	UseFloat = false
end

local function erstellePart(position)
	local part = Instance.new("Part")
	part.Position = position
	part.Anchored = true
	part.Size = Vector3.new(1, 1, 1)
	part.BrickColor = BrickColor.new("Bright red")
	part.Parent = game.Workspace
	part.CanCollide = false
	part.Transparency = 0.65

	task.spawn(function()
		task.wait(10)
		part:Destroy()
	end)

end

local function followPathV2(destination)

	local PathfindingService = game:GetService("PathfindingService")
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")


	local player = Players.LocalPlayer
	local character = player.Character
	local humanoid = character:WaitForChild("Humanoid")
	local HumanoidRootPart = character:WaitForChild("HumanoidRootPart")

	local path = PathfindingService:CreatePath()

	local GoodAndFinished = false

	-- Compute the path
	local success, errorMessage = pcall(function()
		path:ComputeAsync(character.PrimaryPart.Position, destination)
	end)

	if success and path.Status == Enum.PathStatus.Success then
		-- Get the path waypoints
		waypoints = path:GetWaypoints()

		-- Detect if path becomes blocked
		blockedConnection = path.Blocked:Connect(function(blockedWaypointIndex)
			-- Check if the obstacle is further down the path
			if blockedWaypointIndex >= nextWaypointIndex then
				-- Stop detecting path blockage until path is re-computed
				blockedConnection:Disconnect()
				-- Call function to re-compute new path
				followPath(destination)
			end
		end)

		-- Detect when movement to next waypoint is complete
		if not reachedConnection then
			reachedConnection = humanoid.MoveToFinished:Connect(function(reached)
				if reached and nextWaypointIndex < #waypoints then
					-- Increase waypoint index and move to next waypoint
					nextWaypointIndex = nextWaypointIndex + 1
					humanoid:MoveTo(waypoints[nextWaypointIndex].Position)
				else
					reachedConnection:Disconnect()
					blockedConnection:Disconnect()
				end
			end)
		end

		-- Initially move to second waypoint (first waypoint is path start; skip it)
		if GoodAndFinished == true then return nil end
		nextWaypointIndex = 2
		for i = 1,#waypoints do
			erstellePart(waypoints[i].Position + Vector3.new(0,2,0))
		end

		for i = 1,#waypoints do
			HumanoidRootPart.CFrame = CFrame.new(waypoints[i].Position + Vector3.new(0,2,0))
			task.wait(0.2) -- 0.1
		end

		task.wait(2)

		GoodAndFinished = true

		return true

	else
		warn("Path not computed!", errorMessage)
		local tpservice= game:GetService("TeleportService")
		local plr = game.Players.LocalPlayer
		task.wait(1)
		--tpservice:Teleport(game.PlaceId, plr)
		return errorMessage
	end
end

local TeleportV4Wait = false
function TeleportV4(Position)

	local ISARENDER = nil

	--[[

	if LASTTWEEN == nil then
		warn("Tween ist nil!")
	else
		LASTTWEEN:Cancel()
	end

	]]

	if Position ~= nil then
		--[[

	if typeof(Position)=="Vector3" then
		local dist=(game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").Position-Position).Magnitude
		if dist < 3 then
			game.Players.LocalPlayer.Character:MoveTo(Position)
			task.wait()
			return nil
		end
	end

		]]
		if _G.TeleportMethod == "Tween" then
			TweenTp(Position)
			task.wait()
			return true
		elseif _G.TeleportMethod == "TweenV2" then	

			if typeof(Position)=="Vector3" then
				if Position.Y then
					local HUM = game.Players.LocalPlayer.Character.HumanoidRootPart
					game.Players.LocalPlayer.Character:MoveTo(Vector3.new(HUM.Position.X, Position.Y, HUM.Position.Z))
				end
			end

			local dist=(game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").Position-Position).Magnitude
			tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(dist/30, Enum.EasingStyle.Linear)
			local ALRE = true
			tween = tweenService:Create(game:GetService("Players")["LocalPlayer"].Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(Position)})
			CROPTWEEN22 = tween
			LASTTWEEN = tween
			tween:Play()

			task.wait()
			return true
		elseif _G.TeleportMethod == "TweenV3" then	
			local PartToMove = game.Players.LocalPlayer.Character.HumanoidRootPart
			local TargetPos = CFrame.new(Position)
			local Dis = (PartToMove.Position - Vector3.new(TargetPos.X, TargetPos.Y, TargetPos.Z)).Magnitude
			local _speed = 15

			local Completed = false
			if Dis < 30 then
				_speed = 15
			end

			if Dis < 10 then
				_speed = 20
			end


			_speed = _speed


			local TimeToRun = TweenInfo.new(Dis/_speed)

			local WhatToChange = {
				CFrame = TargetPos
			} -- sets CFrame to localplayers position + 30 on the Y axis (brings you upwards)
			-- to limit the player and to not allow them to move, you can uncomment anchored below


			function Noclip(V)
				if V == true then
					V = false
				else
					V = true
				end
				for _, child in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
					if child:IsA("BasePart") and child.CanCollide == true then
						child.CanCollide = V
					end
				end
			end

			function DoAfter()
				PartToMove.Anchored = false
				Noclip(false)
				Completed = true
			end



			local tween = game:GetService("TweenService"):Create(PartToMove, TimeToRun, WhatToChange)
			CROPTWEEN22 = tween
			LASTTWEEN = tween
			Noclip(true)
			task.spawn(function()
				repeat 
					task.wait()
					game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(PartToMove.Position.X, TargetPos.Y, PartToMove.Position.Z))

				until Completed == true
			end)
			tween:Play()
			tween.Completed:Connect(DoAfter)

		elseif _G.TeleportMethod == "Instant" then
			UseFloat = true
			game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").CFrame = CFrame.new(Position)
			FloatRender:Disconnect()
			FloatPart:Destroy()
			task.spawn(function()
				task.wait(0.2)
				UseFloat = false
			end)
			return true
		elseif _G.TeleportMethod == "MiniTp" then
			if TeleportV4Wait == false then
				TeleportV4Wait = true
				MiniTp(Position)
				task.wait()
				TeleportV4Wait = false
				FloatRender:Disconnect()
				FloatPart:Destroy()
				task.wait()
				return true
			end
		elseif _G.TeleportMethod == "Pathfinding" then
			local PART = Instance.new("Part")
			PART.CFrame = CFrame.new(Position)
			PART.Anchored = true
			PART.Transparency = 1
			PathFindingSystem(PART)
			return true
		elseif _G.TeleportMethod == "PathfindingV2" then
			followPathV2(Position)
			return true
		elseif _G.TeleportMethod == "Bypass" then
			ISARENDER = game:GetService("RunService").RenderStepped:Connect(function()
				for i = 1,5 do
					wait(0.1)
					task.spawn(function()
						game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(Position)
					end)
				end
			end)
		end
	else
		warn("Position ist nil!")
	end

	if ISARENDER then
		task.wait(5)
		ISARENDER:Disconnect()
	end

end
-- Tables --

local currentDate = os.date("*t")
local month = currentDate.month
local day = currentDate.day

local holidayMessage = ""

if month == 12 and day == 25 then
	holidayMessage = "🎄"
elseif month == 10 and day == 31 then
	holidayMessage = "🎃"
elseif month == 12 and day == 31 then
	holidayMessage = "🎆"
else
	holidayMessage = ""
end



local Window 
local Tabs


if DeveloperVersion == false then
	if DidKey == true then
		Window = Fluent:CreateWindow({
			Title = "Islands.God "..ScriptVersion.." [FREE!] "..holidayMessage,
			SubTitle = "by NtOpenProcess and soldo_io", -- neverloseyoursmile_88
			TabWidth = 160,
			Size = UDim2.fromOffset(580, 460),
			Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirely
			Theme = "Dark",
			MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
		})

		Tabs = {
			Main = Window:AddTab({ Title = "Main", Icon = "sword" }),
			Teleports = Window:AddTab({ Title = "Teleports", Icon = "bus" }),
			BlockPrinter = Window:AddTab({ Title = "Block Printer", Icon = "printer" }),
			Player = Window:AddTab({ Title = "Player", Icon = "PlayerIcon" }),
			VendingSniper = Window:AddTab({ Title = "Vending Sniper", Icon = "file-search" }),
			BypassFun = Window:AddTab({ Title = "Bypass.Fun", Icon = "server" }),
			Other = Window:AddTab({ Title = "Other", Icon = "sidebar" }),
			Settings = Window:AddTab({ Title = "Settings", Icon = "settings" }),
			Premium = Window:AddTab({ Title = "Premium", Icon = "star" })
		}

	else

		Window = Fluent:CreateWindow({
			Title = "Islands.God "..ScriptVersion.." [Premium!] "..holidayMessage,
			SubTitle = "by NtOpenProcess and soldo_io", -- neverloseyoursmile_88
			TabWidth = 160,
			Size = UDim2.fromOffset(580, 460),
			Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirely
			Theme = "Dark",
			MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
		})

		Tabs = {
			Main = Window:AddTab({ Title = "Main", Icon = "sword" }),
			Teleports = Window:AddTab({ Title = "Teleports", Icon = "bus" }),
			BlockPrinter = Window:AddTab({ Title = "Block Printer", Icon = "printer" }),
			Player = Window:AddTab({ Title = "Player", Icon = "PlayerIcon" }),
			VendingSniper = Window:AddTab({ Title = "Vending Sniper", Icon = "file-search" }),
			BypassFun = Window:AddTab({ Title = "Bypass.Fun", Icon = "server" }),
			Other = Window:AddTab({ Title = "Other", Icon = "sidebar" }),
			Settings = Window:AddTab({ Title = "Settings", Icon = "settings" }),
		}
	end
else
	Window = Fluent:CreateWindow({
		Title = "Islands.God "..ScriptVersion.." [Developer!] "..holidayMessage,
		SubTitle = "by NtOpenprocess and soldo_io", -- neverloseyoursmile_88
		TabWidth = 160,
		Size = UDim2.fromOffset(580, 460),
		Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirely
		Theme = "Dark",
		MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
	})

	Tabs = {
		Main = Window:AddTab({ Title = "Main", Icon = "sword" }),
		Teleports = Window:AddTab({ Title = "Teleports", Icon = "bus" }),
		BlockPrinter = Window:AddTab({ Title = "Block Printer", Icon = "printer" }),
		Player = Window:AddTab({ Title = "Player", Icon = "PlayerIcon" }),
		VendingSniper = Window:AddTab({ Title = "Vending Sniper", Icon = "file-search" }),
		BypassFun = Window:AddTab({ Title = "Bypass.Fun", Icon = "server" }),
		Other = Window:AddTab({ Title = "Other", Icon = "sidebar" }),
		Settings = Window:AddTab({ Title = "Settings", Icon = "settings" }),
		DeveloperTab = Window:AddTab({ Title = "Dev", Icon = "" }),
	}
end 


local Options = Fluent.Options

if DidKey == true then 

	local H = Tabs.Premium:AddParagraph({
		Title = "Why Premium?",
		Content = "with Premium you Get Faster&Beta Updates!"
	})

	local H = Tabs.Premium:AddParagraph({
		Title = "How to buy?",
		Content = "Join discord.gg/MbsxuDEzgT and open a ticket."
	})

	local H = Tabs.Premium:AddParagraph({
		Title = "What Payment Methods?",
		Content = "You can buy the Script with:\n1.Paypal\n2.Robux"
	})

	local H = Tabs.Premium:AddParagraph({
		Title = "How much does it cost?",
		Content = "1.Paypal: 2$\n2.Robux:800R$"
	})

	local H = Tabs.Premium:AddParagraph({
		Title = "Why do you wait?",
		Content = "Go buy Premium!"
	})

	Tabs.Premium:AddButton({
		Title = "Copy Server Invite",
		Description = "",
		Callback = function()
			setclipboard("discord.gg/MbsxuDEzgT")
		end
	})

end


-- // functions \\ --

IYMouse = game.Players.LocalPlayer:GetMouse()
Players = game.Players
iyflyspeed = 1
function NOFLY()
	FLYING = false
	if flyKeyDown or flyKeyUp then flyKeyDown:Disconnect() flyKeyUp:Disconnect() end
	if Players.LocalPlayer.Character:FindFirstChildOfClass('Humanoid') then
		Players.LocalPlayer.Character:FindFirstChildOfClass('Humanoid').PlatformStand = false
	end
	pcall(function() workspace.CurrentCamera.CameraType = Enum.CameraType.Custom end)
end


function sFLY(vfly)
	repeat wait() until IYMouse
	if flyKeyDown or flyKeyUp then flyKeyDown:Disconnect() flyKeyUp:Disconnect() end

	T = Players.LocalPlayer.Character.HumanoidRootPart
	CONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
	lCONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
	SPEED = 0

	local function FLY()
		FLYING = true
		local BG = Instance.new('BodyGyro')
		local BV = Instance.new('BodyVelocity')
		BG.P = 9e4
		BG.Parent = T
		BV.Parent = T
		BG.maxTorque = Vector3.new(9e9, 9e9, 9e9)
		BG.cframe = T.CFrame
		BV.velocity = Vector3.new(0, 0, 0)
		BV.maxForce = Vector3.new(9e9, 9e9, 9e9)
		task.spawn(function()
			repeat wait()
				if not vfly and Players.LocalPlayer.Character:FindFirstChildOfClass('Humanoid') then
					Players.LocalPlayer.Character:FindFirstChildOfClass('Humanoid').PlatformStand = true
				end
				if CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0 or CONTROL.Q + CONTROL.E ~= 0 then
					SPEED = 50
				elseif not (CONTROL.L + CONTROL.R ~= 0 or CONTROL.F + CONTROL.B ~= 0 or CONTROL.Q + CONTROL.E ~= 0) and SPEED ~= 0 then
					SPEED = 0
				end
				if (CONTROL.L + CONTROL.R) ~= 0 or (CONTROL.F + CONTROL.B) ~= 0 or (CONTROL.Q + CONTROL.E) ~= 0 then
					BV.velocity = ((workspace.CurrentCamera.CoordinateFrame.lookVector * (CONTROL.F + CONTROL.B)) + ((workspace.CurrentCamera.CoordinateFrame * CFrame.new(CONTROL.L + CONTROL.R, (CONTROL.F + CONTROL.B + CONTROL.Q + CONTROL.E) * 0.2, 0).p) - workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
					lCONTROL = {F = CONTROL.F, B = CONTROL.B, L = CONTROL.L, R = CONTROL.R}
				elseif (CONTROL.L + CONTROL.R) == 0 and (CONTROL.F + CONTROL.B) == 0 and (CONTROL.Q + CONTROL.E) == 0 and SPEED ~= 0 then
					BV.velocity = ((workspace.CurrentCamera.CoordinateFrame.lookVector * (lCONTROL.F + lCONTROL.B)) + ((workspace.CurrentCamera.CoordinateFrame * CFrame.new(lCONTROL.L + lCONTROL.R, (lCONTROL.F + lCONTROL.B + CONTROL.Q + CONTROL.E) * 0.2, 0).p) - workspace.CurrentCamera.CoordinateFrame.p)) * SPEED
				else
					BV.velocity = Vector3.new(0, 0, 0)
				end
				BG.cframe = workspace.CurrentCamera.CoordinateFrame
			until not FLYING
			CONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
			lCONTROL = {F = 0, B = 0, L = 0, R = 0, Q = 0, E = 0}
			SPEED = 0
			BG:Destroy()
			BV:Destroy()
			if Players.LocalPlayer.Character:FindFirstChildOfClass('Humanoid') then
				Players.LocalPlayer.Character:FindFirstChildOfClass('Humanoid').PlatformStand = false
			end
		end)
	end
	flyKeyDown = IYMouse.KeyDown:Connect(function(KEY)
		if KEY:lower() == 'w' then
			CONTROL.F = (iyflyspeed)
		elseif KEY:lower() == 's' then
			CONTROL.B = - (iyflyspeed)
		elseif KEY:lower() == 'a' then
			CONTROL.L = - (iyflyspeed)
		elseif KEY:lower() == 'd' then 
			CONTROL.R =  (iyflyspeed)
		elseif QEfly and KEY:lower() == 'e' then
			CONTROL.Q = iyflyspeed*2
		elseif QEfly and KEY:lower() == 'q' then
			CONTROL.E = -iyflyspeed*2
		end
		pcall(function() workspace.CurrentCamera.CameraType = Enum.CameraType.Track end)
	end)
	flyKeyUp = IYMouse.KeyUp:Connect(function(KEY)
		if KEY:lower() == 'w' then
			CONTROL.F = 0
		elseif KEY:lower() == 's' then
			CONTROL.B = 0
		elseif KEY:lower() == 'a' then
			CONTROL.L = 0
		elseif KEY:lower() == 'd' then
			CONTROL.R = 0
		elseif KEY:lower() == 'e' then
			CONTROL.Q = 0
		elseif KEY:lower() == 'q' then
			CONTROL.E = 0
		end
	end)
	FLY()
end



function Hash()
	local HttpService = game:GetService("HttpService")
	local Abd = HttpService:GenerateGUID(false)..HttpService:GenerateGUID(false)..HttpService:GenerateGUID(false)
	return Abd
end

local _WAIT = false
function TweenTp(...)

	local _speed=_G.TweenFlySpeed or 30

	local TFS = SettingsTable

	if not game.Players.LocalPlayer.Character then return end
	if _WAIT == false then
		_WAIT = true

		if TFS.TweenFly == true then
			sFLY(true)
		end


		if TFS.Twennnoclip == true then
			for _, child in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
				if child:IsA("BasePart") and child.CanCollide == true and child.Name ~= floatName then
					child.CanCollide = false
				end
			end
		end

		local plr=game.Players.LocalPlayer
		local args={...}
		if typeof(args[1])=="number"and args[2]and args[3]then
			args=Vector3.new(args[1],args[2],args[3])
		elseif typeof(args[1])=="Vector3" then
			args=args[1]    
		elseif typeof(args[1])=="CFrame" then
			args=args[1].Position
		end
		if plr.Character:FindFirstChild("HumanoidRootPart") then

			local dist=(plr.Character:FindFirstChild("HumanoidRootPart").Position-args).Magnitude

			--[[

			if dist > 100 then
				if TFS.TweenFast == true then
					_speed = math.random(25,30)
				end
			end


			]]


			local Tween = game:GetService("TweenService"):Create(
			plr.Character.HumanoidRootPart,
			TweenInfo.new(dist/_speed,Enum.EasingStyle.Linear),
			{CFrame=CFrame.new(args)}
			)

			CROPTWEEN22 = Tween
			LASTTWEEN = Tween
			Tween:Play()
			Tween.Completed:Connect(function()
				_WAIT = false
				if TFS.PlayerFly == false then
					NOFLY()
				end
				if TFS.Twennnoclip == true then
					for _, child in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
						if child:IsA("BasePart") and child.CanCollide == false and child.Name ~= floatName then
							child.CanCollide = true
						end
					end
				end
				return true
			end)
			return Tween
		end
	end
end

function PathFindingSystem(dest)
	local serv = game:GetService("PathfindingService")
	local human = game.Players.LocalPlayer.Character.Humanoid 
	local body = game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart") or game.Players.LocalPlayer.Character:FindFirstChild("Torso")
	if dest == nil then return end
	if dest:IsA("Part") then else DebugCheck(0,"Fehler kein Part!") end
	local path = serv:CreatePath()
	path:ComputeAsync(body.Position,dest.Position)
	if path.Status == Enum.PathStatus.Success then
		local wayPoints = path:GetWaypoints()
		for i = 1,#wayPoints do
			local point = wayPoints[i]
			human:MoveTo(point.Position)
			local success = human.MoveToFinished:Wait()
			if point.Action == Enum.PathWaypointAction.Jump then
				human.WalkSpeed = 0
				wait(0.2)
				human.WalkSpeed = 16
				human.Jump = true
			end
			if not success then
				human.Jump = true
				human:MoveTo(point.Position)
				if not human.MoveToFinished:Wait() then
					break
				end
			end
		end
	end
end

function ChestAura()
	for i,Chest in pairs(GetIsland():FindFirstChild("Blocks"):GetChildren()) do
		if Chest:FindFirstChild("Contents") then
			for i,Tool in pairs(Chest:FindFirstChild("Contents"):GetChildren()) do
				local args = {
					[1] = {
						["chest"] = Chest,
						["player_tracking_category"] = "join_from_web",
						["amount"] = Tool:FindFirstChild("Amount").Value,
						["tool"] = Tool,
						["action"] = "withdraw"
					}
				}

				game:GetService("ReplicatedStorage"):WaitForChild("rbxts_include"):WaitForChild("node_modules"):WaitForChild("@rbxts"):WaitForChild("net"):WaitForChild("out"):WaitForChild("_NetManaged"):WaitForChild("CLIENT_CHEST_TRANSACTION"):InvokeServer(unpack(args))

			end
		end
	end
	task.wait()
end

function GetTreeName(TreeArt)
	_G.ZahlenTree = false
	_G.OakSelected = false
	if TreeArt == "all" then
		return "tree"
	elseif TreeArt == "Oak" then
		_G.OakSelected = true
		return "tree"
	elseif TreeArt == "Birch" then
		return "treeBirch"
	elseif TreeArt == "Maple" then
		return "treeMaple"
	elseif TreeArt == "Pine" then
		return "treePine"
	elseif TreeArt == "Hickory" then
		return "treeHickory"
	elseif TreeArt == "Spirit" then
		_G.ZahlenTree = true
		return "treeSpirit"
	end
end


function IsSynapse()
	if (syn) then
		return true
	else
		return false
	end
end


function GetIsland()
	local FOUND = false
	local islandName
	local _________Inseln = game:GetService("Workspace").Islands:GetChildren()
	for i = 1, #_________Inseln do
		if _________Inseln[i]:FindFirstChild("Owners"):FindFirstChild(_G.Island_USERID) then
			islandName = _________Inseln[i]
			FOUND = true
			return islandName
		end
	end 
	task.wait()
	if not FOUND then
		return game:GetService("Workspace").Islands:FindFirstChildWhichIsA("Model")
	end
end


function OwnISland()
	local islandName = GetIsland()
	local args = {
		[1] = {
			["island"] = islandName
		}
	}
	if islandName and islandName ~= nil then
		game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_VISIT_ISLAND_REQUEST:InvokeServer(unpack(args))
	end
end

local SAVEDBlocksPos = {}

function GetBlockUpdate()
	local Island = GetIsland()
	if Island then
		local Blocks = Island:FindFirstChild("Blocks")

		for i,v in pairs(Blocks:GetChildren()) do
			if v:IsA("Part") or v:IsA("MeshPart") then
				table.insert(SAVEDBlocksPos, v)
			end
		end 
	end
end

GetBlockUpdate()

function GetBlock(Name, Pos)


	if SAVEDBlocksPos == {} or SAVEDBlocksPos == nil then
		GetBlockUpdate()
	end

	local Island = GetIsland()
	local Blocks = Island:FindFirstChild("Blocks")
	if not Blocks then return nil end

	for i,v in ipairs(SAVEDBlocksPos) do
		if v:FindFirstChild("Health") then
			if Name == false then
				if v.Position == Pos then
					return v
				end
			else
				if v.Name == Name then
					if v.Position == Pos then
						return v
					end
				end
			end
		end
	end
end

function GetBlocks(position, size, Part)

	local mainPart

	if Part then

		mainPart = Part

	else
		local position = position or Vector3.new(0,0, 0) -- Ersetzen Sie die Position nach Bedarf
		local halfSize = size or Vector3.new(0,0,0) -- Regiongröße von 10x10x10


		-- Erstellen eines Parts und Platzierung innerhalb der Region
		mainPart = Instance.new("Part")
		mainPart.Size = halfSize
		mainPart.CFrame = CFrame.new(position)
		mainPart.Anchored = true
		mainPart.Parent = workspace
		mainPart.Transparency = 0.5
		mainPart.CanCollide = false

		-- Erstellen einer SelectionBox und Platzierung um die Region

		print("Erstellen einer SelectionBox und Platzierung um die Region")

		local selectionBox = Instance.new("SelectionBox")
		selectionBox.Adornee = mainPart
		selectionBox.LineThickness = 0.1
		selectionBox.Color3 = Color3.new(1, 0, 0)
		selectionBox.Transparency = 0.5
		selectionBox.Parent = mainPart

	end


	local FoundBlocks  = {}

	-- Drucken der Blöcke innerhalb der Region mit ihren Namen
	local blockCount = 0
	for _, part in pairs(workspace:GetPartsInPart(mainPart)) do
		blockCount = blockCount + 1
		DebugCheck(0,"Block", blockCount, "Name:", part.Name, "Position:", part.Position)
		table.insert(FoundBlocks, part)
	end
	return FoundBlocks
end

function GetMobName(Mob)
	if Mob == "Slime" then
		return "slime"
	end
end

function Message(Title1, Context1, ButtonText1, DurationTime)
	Fluent:Notify({
		Title = Title1,
		Content = Context1,
		Duration = DurationTime
	})
end



local RemoteMobCooldown = false
game:GetService("RunService").RenderStepped:Connect(function()
	if _G.MobRemoteSpamming == true then
		local MOB = _G.MobRemoteSpammingSelectedMob
		local args = {
			[1] = Hash(),
			[2] = {
				[1] = {
					["direction"] = Vector3.new(0,-90,0), -- MOB:FindFirstChild("HumanoidRootPart").Position
					["shootType"] = 0,
					["acaanSbvNqmvUwqyaPbPdbs"] = "\7\240\159\164\163\240\159\164\161\7\n\7\n\7\niDtnsvjyuiGm",
					["spellBook"] = game:GetService("Players").LocalPlayer.Character:FindFirstChildWhichIsA("Tool"),
					["charge"] = 1,
					["time"] = game.Workspace.DistributedGameTime
				}
			}
		}


		if RemoteMobCooldown == false then
			RemoteMobCooldown = true
			game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild("kthdgIcgPfwv/tyTrpdkeydznlntEvsjocmEixLw"):FireServer(unpack(args))
			task.wait()
			RemoteMobCooldown = false
		end
	end
end)



function DoubleFarmMob(V)
	DebugCheck(0,"DoubleFarmMob")
	local SelectedMob
	local ISAMOB = false
	for i,v in pairs(_G.SelectedMobs) do
		task.wait()
		if game:GetService("Workspace").WildernessIsland.Entities:FindFirstChild(v) then
			if ISAMOB == false then 
				ISAMOB = true
				SelectedMob = game:GetService("Workspace").WildernessIsland.Entities:FindFirstChild(v)
				DebugCheck(0,SelectedMob.Name)
			end
		end
	end

	if SelectedMob ~= nil and SelectedMob then

		local YVALUE = _G.MobTpYPos

		if SelectedMob:FindFirstChild("HumanoidRootPart") == nil then SelectedMob:Destroy() return end


		TeleportV4(SelectedMob:FindFirstChild("HumanoidRootPart").Position + Vector3.new(0,YVALUE,0))


		for i = 1,3 do
			if SelectedMob then
				if SelectedMob:FindFirstChild("HumanoidRootPart") then

					TeleportV4(SelectedMob:FindFirstChild("HumanoidRootPart").Position + Vector3.new(0,YVALUE,0))


					if CANUSEAUTOCLICKER == true then
						if _G.MobBookFarm == true then
							_G.MobRemoteSpammingSelectedMob = SelectedMob
							_G.MobRemoteSpamming = true
						else

							game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
							task.wait()
							game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)
						end
					end
					if _G.MobBookFarm == false then 
						if 	SelectedMob:FindFirstChild("HumanoidRootPart") then
							--[[
														if SelectedMob:FindFirstChild("Humanoid") then
								SelectedMob:FindFirstChild("Humanoid"):Destroy()
							end
							]]
							--SelectedMob:FindFirstChild("HumanoidRootPart").Size = Vector3.new(8,YVALUE+4,8)
							--SelectedMob:FindFirstChild("HumanoidRootPart").CanCollide = false
						end
					end
					task.wait()
				end
			end
		end
	end
end



local MOBSWORDBYPASSED = false
local ANTIBANMOB = false

local ANTICONSOLEWARNLOGANIMATION = false

local LastMob = nil

game:GetService("RunService").RenderStepped:Connect(function()
	if _G.AutoFarm == true or _G.BossAutoFarm == true then	
		if LastMob and LastMob:FindFirstChild("Humanoid") and LastMob:FindFirstChild("Humanoid").Health > 0 and LastMob:FindFirstChild("HumanoidRootPart") then
			local YVALUE = _G.MobTpYPos
			TeleportV4(LastMob:FindFirstChild("HumanoidRootPart").Position + Vector3.new(0,YVALUE,0))
		end
	end
end)

function FarmMob(V)

	print("FarmMob:",V)

	local function findNearestMob(A)
		local closestPart = nil
		local closestDistance = math.huge
		local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

		local Table = A

		for i, part in ipairs(Table) do
			local distance = (part:FindFirstChild("HumanoidRootPart").Position - playerPosition).magnitude
			if distance < closestDistance then
				closestPart = part
				closestDistance = distance
			end
		end

		DebugCheck(0,"findNearestPart")

		return closestPart
	end

	if _G.AutoFarm == false and _G.BossAutoFarm == false then return nil end
	DebugCheck(0,"FarmMob")
	local SelectedMob

	local MobsToScan = {}
	if V == true then
		SelectedMob = game:GetService("Workspace").WildernessIsland.Entities:FindFirstChild(_G.SelectedBoss)
	else


		for i,v in pairs(game:GetService("Workspace").WildernessIsland.Entities:GetChildren()) do
			if v and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") then
				print("HUMANOID/ROOTAPRT")
				if type(_G.SelectedMob) == "table" then
					for i,x in pairs(_G.SelectedMob) do
						if v.Name == x then
							print("ADDED!",v.Name)
							table.insert(MobsToScan, v)
						else
							print("x ist:",x.." Mob heißt:",v)
						end
					end
				else
					if v.Name == _G.SelectedMob then
						print("ADDED!",v.Name)
						table.insert(MobsToScan, v)
					else
						print(v.Name)
					end
				end
			end
		end

		SelectedMob = findNearestMob(MobsToScan)
		print("NEWMOB:",SelectedMob)
	end
	if SelectedMob ~= nil and SelectedMob then

		LastMob = SelectedMob

		print(0,"Farm Mob:", SelectedMob.Name)

		local YVALUE = _G.MobTpYPos

		task.spawn(function()
			TeleportV4(SelectedMob:FindFirstChild("HumanoidRootPart").Position + Vector3.new(0,YVALUE,0))
		end)
		print(0,"MOB FARM ON TOP!")

		if MOBSWORDBYPASSED == false then
			if _G.ragebladeMobFarm == true then

				local success, result = pcall(function()
					local aux = loadstring(auxLocal)()

					local Tool = game:GetService("Players").LocalPlayer.Character:FindFirstChild("rageblade")
					if Tool then
						local aux = loadstring(auxLocal)()

						local scriptPath = Tool:FindFirstChild("rageblade")
						local closureName = "Unnamed function"
						local upvalueIndex = 1
						local closureConstants = {
							[1] = "isHitting",
							[2] = "getLivingEntityFromChildPart",
							[3] = "attemptHit"
						}
						print("scriptPath:",scriptPath)


						local closure = aux.searchClosure(scriptPath, closureName, upvalueIndex, closureConstants)
						local value = 0
						local elementIndex = "lastClicked"

						game:GetService("RunService").RenderStepped:Connect(function()
							debug.getupvalue(closure, upvalueIndex)[elementIndex] = value
						end)

					end
					-- Generated by Hydroxide's Upvalue Scanner: https://github.com/Upbolt/Hydroxide



					local aux = loadstring(auxLocal)()

					local Tool = game:GetService("Players").LocalPlayer.Character:FindFirstChild("rageblade")
					if Tool then
						local scriptPath = Tool:FindFirstChild("rageblade")
						local closureName = "Unnamed function"
						local upvalueIndex = 1
						local closureConstants = {
							[1] = "isHitting",
							[2] = "getLivingEntityFromChildPart",
							[3] = "attemptHit"
						}

						local closure = aux.searchClosure(scriptPath, closureName, upvalueIndex, closureConstants)
						local value = 4
						local elementIndex = "speed"


						debug.getupvalue(closure, upvalueIndex)[elementIndex] = value
						MOBSWORDBYPASSED = true
					end
				end)
			end
		end

		for i = 1,1 do
			if _G.AutoFarm == false and _G.BossAutoFarm == false then return end
			if SelectedMob then
				if SelectedMob:FindFirstChild("HumanoidRootPart") then

					TeleportV4(SelectedMob:FindFirstChild("HumanoidRootPart").Position + Vector3.new(0,YVALUE,0))


					if CANUSEAUTOCLICKER == true then
						if _G.MobBookFarm == true then
							_G.MobRemoteSpammingSelectedMob = SelectedMob
							_G.MobRemoteSpamming = true
						else

							--if ANTIBANMOB == false then
							--	ANTIBANMOB = true

							task.spawn(function()
								if ANTICONSOLEWARNLOGANIMATION == false then
									ANTICONSOLEWARNLOGANIMATION = true
									for i,v in pairs(game:GetService('Players'):GetChildren()) do
										if v and v.Character and v.Character:FindFirstChild("Humanoid") then
											Player = v.Name
											AnimationId = "5328169716"
											local Anim = Instance.new("Animation")
											Anim.AnimationId = "rbxassetid://"..AnimationId
											local k = game.Players[Player].Character.Humanoid:LoadAnimation(Anim)
											k:Play() --Play the animation
											k:AdjustSpeed(0)
											task.spawn(function()
												task.wait(8)
												Anim:Destroy()
											end)	
												--[[

												if _G.MobFarmAnimationBypass == true then
													k:AdjustSpeed(0)
												else
													k:AdjustSpeed(1)
												end

												]]
										end
									end
									task.wait(1)
									ANTICONSOLEWARNLOGANIMATION = false
								end
							end)

								--[[

								game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
								game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)

								]]

							task.wait(0.5)

							local args = {
								[1] = Hash(),
								[2] = {
									[1] = {
										[MotHitH1] = MotHitH2,
										["hitUnit"] = SelectedMob
									}
								}
							}

							if  _G.ragebladeMobFarm == true  then
								for i = 1,50 do
									game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("KillRemote").Value):FireServer(unpack(args))
									task.wait()
								end
							else
								for i = 1,5 do
									game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("KillRemote").Value):FireServer(unpack(args))
									task.wait(0.3)
								end
							end

							--ANTIBANMOB = false
							--end
						end

					end
				end
			end
		end
	else
		print("No SelectedMob!")
	end
end

function GetProxNameFromBoss(BossName)
	if BossName == "slimeKing" then
		return "slime_king_spawn"
	elseif BossName == "slimeQueen" then
		return "slime_queen_spawn"
	elseif BossName == "desertBoss" then
		return "desert_boss_spawn"
	elseif BossName == "golem" then
		return "golem_spawn"
	end 
end


function SpawnBoss(BossName)
	if BossName then
		local PProx = game:GetService("Workspace").spawnPrefabs.WildEventTriggers:FindFirstChild(BossName)
		if PProx then
			local RealProx = PProx:FindFirstChild("ProximityPrompt")
			if RealProx then
				TeleportV4(PProx.Position)
				fireproximityprompt(RealProx)
			end 
		end
	end
end

local BossCheckCOOLDOWN = false
function BossCheck(BossName)
	if BossCheckCOOLDOWN == false then
		BossCheckCOOLDOWN = true
		local SelectedMob = game:GetService("Workspace").WildernessIsland.Entities:FindFirstChild(BossName)
		if SelectedMob then
			FarmMob(true)
		else 
			if _G.BossAutoSpawn == true then
				SpawnBoss(GetProxNameFromBoss(BossName))
			else
				print("Auto Spawn ist off, ich warte dann mal ^^")
			end
		end
		task.wait(0.1)
		BossCheckCOOLDOWN = false
	end
end

local CropAntiLag = false
function CropFarm(TP)
	if CropAntiLag == false then
		CropAntiLag = true

		local Island = GetIsland() 
		local Blocks = Island:FindFirstChild("Blocks") 

		local ToFarm = {}
		local ReplaceCFrame = {}

		local Count = 1

		local CC = 0


		for i,v in pairs(Blocks:GetChildren()) do
			if v.Name == _G.SelectedCrop then
				local dis = (v.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude

				local MAXDIS = _G.SichleCropRange or 30

				if dis < MAXDIS then
					--table.insert(ToFarm, v) -- add the light
					CC = CC +1
					ToFarm[CC] = v
					ReplaceCFrame[CC] = v.CFrame
				end
			end
		end



		if TP == true then
			if Blocks:FindFirstChild(_G.SelectedCrop) then
				local A =  Blocks:FindFirstChild(_G.SelectedCrop)
				TeleportV4(A.Position)
				task.wait(0.5)
			end
		end

		for i,v in pairs(ToFarm) do

			local H1 = RemoteData:FindFirstChild("CropHashData").Value
			local H2 = _G.CropHash

			local ohTable1 = {
				[H1] = H2,
				["player"] = game:GetService("Players").LocalPlayer,
				["model"] = ToFarm[Count]
			}


			task.wait()
			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_HARVEST_CROP_REQUEST:InvokeServer(ohTable1)
			Count = Count + 1
		end


		task.wait()

		for i,v in ipairs(ReplaceCFrame) do		



			local ohTable1 = {
				["upperBlock"] = false,
				["cframe"] = v,
				["blockType"] = "wheat",
				[PlaceHASHName] = CropPlaceH2
			}

			if _G.AutoReplaceCrop == true then
				game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(ohTable1)
			end

			v = nil
		end


	end
	task.wait(5)
	CropAntiLag = false
end

local AutoCollectFruitsCooldown = false
function AutoCollectFruits()
	if AutoCollectFruitsCooldown == false then
		AutoCollectFruitsCooldown = true
		local Island = GetIsland()
		for i,v in pairs(Island:FindFirstChild("Blocks"):GetChildren()) do
			if v:FindFirstChild("FruitLocations") then
				for i,v in pairs(v:FindFirstChild("FruitLocations"):GetChildren()) do
					if v:IsA("Part") then
						if v:FindFirstChild("Targettable") then
							if v:FindFirstChildWhichIsA("Tool") then
								local dis = (v.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								if dis < 30 then
									local args = {
										[1] = {
											["tool"] = v:FindFirstChildWhichIsA("Tool"),
											[PickupH1] = PickupH2
										}
									}

									game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_TOOL_PICKUP_REQUEST:InvokeServer(unpack(args))

								else
									repeat TeleportV4(v.Position)
										local args = {
											[1] = {
												["tool"] = v:FindFirstChildWhichIsA("Tool"),
												[PickupH1] = PickupH2
											}
										}

										game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_TOOL_PICKUP_REQUEST:InvokeServer(unpack(args))

										task.wait(1)
									until v:FindFirstChildWhichIsA("Tool") == nil
								end
							end
						end
					end
				end
			end
		end
		task.wait()
		AutoCollectFruitsCooldown = false
	end
end

local FishFarmCooldown = false
function FishFarm()
	local dis = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Vector3.new(-91, 29, -897)).Magnitude

	if dis > 30 then
		TeleportV4(Vector3.new(-91, 34, -897))
		repeat wait() until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - Vector3.new(-91, 29, -897)).Magnitude < 5
		task.wait(0.5)
	end 

	if FishFarmCooldown == false then
		FishFarmCooldown = true
		local args = {
			[1] = Hash(),
			[2] = {
				[1] = {
					["playerLocation"] = Vector3.new(game.Players.LocalPlayer.Character.HumanoidRootPart.Position),
					["direction"] = Vector3.new(-0.9983646869659424, -9.509330567425422e-08, 0.057165950536727905),
					["strength"] = math.random(0.5, 2)
				}
			}
		}

		game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("AngelRemote").Value):FireServer(unpack(args))

		task.wait(math.random(13,15))
		local args = {
			[1] = {
				["success"] = true
			}
		}
		game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("FishFarmFinishRemote").Value):FireServer(unpack(args))

	--[[

		local args = {
		[1] = Hash(),
		[2] = {
			[1] = {}
		}
	}
	
	game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild("jmqvFcP/dgikodtTfngoBWdtu"):FireServer(unpack(args))
	

	]]

		if game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then
			game.Players.LocalPlayer.Character:FindFirstChild("Humanoid").Jump = true
		end 
		task.wait(math.random(0.1,0.3))
		FishFarmCooldown = false
	end
end	

-- Funktion zum Finden des nächsten Teils
local function findNearestPart(A)
	local closestPart = nil
	local closestDistance = math.huge
	local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

	local Table = A

	for i, part in ipairs(Table) do
		local distance = (part.Position - playerPosition).magnitude
		if distance < closestDistance then
			closestPart = part
			closestDistance = distance
		end
	end

	DebugCheck(0,"findNearestPart")

	return closestPart
end

local AutoCollectTotemItemsCooldown = false
function AutoCollectTotemItems()
	if _G.AutoCollectTotemItems == true then
		if AutoCollectTotemItemsCooldown == false then
			AutoCollectTotemItemsCooldown = true
			local Island = GetIsland()
			if Island and Island:FindFirstChild("Blocks") then

				local Totems = {}



				for i,v in pairs(Island:FindFirstChild("Blocks"):GetChildren()) do

					local Items = v:FindFirstChild("WorkerContents") 
					if Items and Items:FindFirstChildWhichIsA("Tool") then
						if v.Name == _G.SelectedTotem then
							table.insert(Totems, v)
						end

					end
				end

				local Totem = findNearestPart(Totems)

				if Totem then
					local v = Totem
					TeleportV4(v.Position)
					repeat wait() until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude < 3
					repeat
						for i,v in pairs(v:FindFirstChild("WorkerContents"):GetChildren()) do
							local args = {
								[1] = {
									["tool"] = v,
									[PickupH1] = PickupH2
								}
							}

							game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_TOOL_PICKUP_REQUEST:InvokeServer(unpack(args))
							task.wait()
						end	
						task.wait(0.3)
					until v:FindFirstChild("WorkerContents") == nil or v:FindFirstChild("WorkerContents"):FindFirstChildWhichIsA("Tool") == nil
					task.wait(1)
				end

			end
		end 
		task.wait(2)
		AutoCollectTotemItemsCooldown = false
	end
end


local TFCO = false
local RemoteAntiBan = false
function TreeFarm(TP)	

	local NE = {}

	if TFCO == true then return nil end

	TFCO = true

	if TP == true then
		DebugCheck(0,"TreeFarm (true)")
	else
		DebugCheck(0,"Tree Farm (false)")
	end


	if _G.SelectedTree == "all" then
		_G.SelectedTree = "tree"
	else
	end

	if _G.SelectedTree == "Oak" then
		DebugCheck(0,"IST OAK!!!")
	end

	DebugCheck(0,"JOA")
	DebugCheck(0,_G.SelectedTree)

	-- Funktion zum Finden des nächsten Teils
	local function findNearestPart(A)
		local closestPart = nil
		local closestDistance = math.huge
		local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

		local Table = A

		for i, part in ipairs(Table) do
			local distance = (part.Position - playerPosition).magnitude
			if distance < closestDistance then
				closestPart = part
				closestDistance = distance
			end
		end

		DebugCheck(0,"findNearestPart")

		return closestPart
	end

	local distance = 35000
	for i,v in pairs(GetIsland().Blocks:GetChildren()) do 

		local Art = string.sub(v.Name:lower(), 1, string.len(_G.SelectedTree)) 
		--if (Art == _G.SelectedTree) then 
		if string.match(v.Name, _G.SelectedTree) then
			if 	_G.OakSelected == true  then
				DebugCheck(0,"isTreeWithNumber")
				local isTreeWithNumber = string.match(v.Name, "^tree%d+$")
				DebugCheck(0,"ADD22???",v.name)
				if isTreeWithNumber then
					DebugCheck(0,"ADD22",v.name)
					table.insert(NE, v)
				end
			elseif _G.ZahlenTree == true then
				local isTreeWithNumber = string.match(v.Name, "^".._G.SelectedTree.."%d+$")
				if isTreeWithNumber then
					DebugCheck(0,"ADD35",v.name)
					table.insert(NE, v)
				end
			else

				DebugCheck(0,"ADD",v.name)
				table.insert(NE, v)
			end
		end
		-- end
	end	


	local v = findNearestPart(NE)

	DebugCheck(0,v)

	if v then

		local mag = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude

		if mag < distance then 

			if _G.TreeAutoFarm == false and _G.TreeAura == false then return end


		--[[

				if TP == true then
			task.spawn(function()
				TeleportV4(v.Position + Vector3.new(0,0,6))
			end)
		end

		]]
			local T = v

			local H1 = RemoteData:FindFirstChild("TreeHashData").Value
			local H2 = _G.TreeHash

			local TFOUND = v:FindFirstChild("trunk") or v:FindFirstChildWhichIsA("MeshPart")

			local args1 = {
				[H1] = H2,
				["part"] = TFOUND,
				["block"] = v,
				["norm"] = Vector3.new(v.CFrame),
				["pos"] = v.Position
			}


			if v == nil then TFCO = false return end
			if TFOUND == nil then TFCO = false return end



		--[[

		if TP == true then
			task.spawn(function()
			TeleportV4(v.Position + Vector3.new(0,0,6))
			end)
		end

		]]

			if v == nil then TFCO = false return end
			if TFOUND == nil then TFCO = false return end

			while TFOUND do
				if v then
					task.wait()
					for i = 1,10 do
						if v ~= nil then
							if _G.TreeAutoFarm == false and _G.TreeAura == false then TFCO = false return end
							if not v or v == nil then TFCO = false return end
							if not TFOUND then TFCO = false return end
							task.wait()
							if RemoteAntiBan == false then
								RemoteAntiBan = true
								if TP == true then
									TeleportV4(v.Position + Vector3.new(0,0,6))
									task.wait()
								end
								game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(args1)
								-- task.wait()
								if v:FindFirstChild("trunk") or v:FindFirstChildWhichIsA("MeshPart") then
								else
									TFOUND = nil
								end
								RemoteAntiBan = false
							end
						end
					end
				else
					task.wait(0.2)
					TFCO = false
					break
				end 
			end
		else
			OwnISland()
		end	 

	end

	task.wait(0.8)

	TFCO = false

end


function ROCKHELPER_1()
	local ohTable1 = {
		[HitHASHName] = HitHASH,
		["part"] =    _G.Now_Rock_part,
		["block"] =  _G.Now_Rock_block,
		["norm"] =   _G.Now_Rock_norm,
		["pos"] = _G.Now_Rock_pos,
	}

	for i = 1,1 do
		if _G.Now_Rock_part then
			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("BlockRemote").Value):InvokeServer(ohTable1)
		end
	end
end

local IslandRockFarmCOOLDOWN = false
function IslandRockFarm(RockArt)
	if IslandRockFarmCOOLDOWN == false then
		IslandRockFarmCOOLDOWN = true
		print("IslandRockFarm")
		-- if _G.RockFarmonIsland ~= true then return nil end
		local function findNearestRock(A)
			local closestPart = nil
			local closestDistance = math.huge
			local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

			local Table = A

			for i, part in ipairs(Table) do
				task.wait()
				local distance = (part.Position - playerPosition).magnitude
				if distance < closestDistance then
					closestPart = part
					closestDistance = distance
				end
			end

			return closestPart
		end


		local Island = GetIsland()
		local Blocks = Island:FindFirstChild("Blocks")

		local RocksSaved = {}

		if type(RockArt) == "table" then
			for i,v in pairs(Blocks:GetChildren()) do

				function removeRock(itemName)
					task.wait()
					local index = string.find(itemName, "rock")
					if index ~= nil then
						return string.sub(itemName, 1, index - 1) .. string.sub(itemName, index + 4)
					else
						return itemName
					end
				end	

				local Name = removeRock(v.Name)

				local isALL = false

				if RockArt == "All" or table.find(RockArt,"All") then

					task.wait()

					if v:IsA("Part") or v:IsA("MeshPart") or v:IsA("BasePart") then

						task.wait()

						table.insert(RocksSaved, v)

						isALL = true

					end

				end

				if table.find(RockArt,Name) and isALL == false then

					task.wait()

					if v:IsA("Part") or v:IsA("MeshPart") or v:IsA("BasePart") then

						task.wait()

						table.insert(RocksSaved, v)

					end

				end
			end
		else
			if RockArt == "All"then
				for i,v in pairs(Blocks:GetChildren()) do
					if v:FindFirstChild("1") then

						if v:IsA("Part") or v:IsA("MeshPart") or v:IsA("BasePart") then

							if _G.RockFarmonIsland ~= true then return nil end

							table.insert(RocksSaved, v)

						end

					end
				end
			else
				for i,v in pairs(Blocks:GetChildren()) do
					if v.Name == RockArt then

						if v:IsA("Part") or v:IsA("MeshPart") or v:IsA("BasePart") then

							if _G.RockFarmonIsland ~= true then return nil end

							table.insert(RocksSaved, v)

						end

					end
				end
			end
		end

		print("HOL DEN BLOCK!!!")

		local v = findNearestRock(RocksSaved)

		if v then

			print("V gefunden!!!", v.Name)

			-- if _G.RockFarmonIsland ~= true then return nil end

			local dis = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude

			print("DISTANCE")

			if dis > 20 then
				print("YES")
				if v then
					TeleportV4(v.Position)
					repeat wait() until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude < 20
					task.wait()
					local ohTable1 = {
						[HitHASHName] = HitHASH,
						["part"] = v:FindFirstChild("1") or v,
						["block"] = v,
						["norm"] = Vector3.new(v.CFrame),
						["pos"] = v.Position
					}
					game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("BlockRemote").Value):InvokeServer(ohTable1)
				else
					v = nil 
				end
			else
				print("NOPE")
				if v then
					print("Es gibt v schicke remote")
					local ohTable1 = {
						[HitHASHName] = HitHASH,
						["part"] = v:FindFirstChild("1") or v,
						["block"] = v,
						["norm"] = Vector3.new(v.CFrame),
						["pos"] = v.Position
					}
					game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("BlockRemote").Value):InvokeServer(ohTable1)
				else
					v = nil
				end
			end

		else
			warn("Kein Block!!!")
		end

	end

	task.wait(1)

	print("WAIT 1 ist UM!!!")

	IslandRockFarmCOOLDOWN = false

end

local RF = false 
function RockFarm(RockArt, T)

	if RF == false then
		RF = true

		if _G.RockFarmonIsland == true then
			IslandRockFarm(RockArt)
			time.sleep(1)
			RF = false
			return 
		end



		local NowName = RockArt
		local Rocks = {}

		local function findNearestRock(A)
			local closestPart = nil
			local closestDistance = math.huge
			local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

			local Table = A

			for i, part in ipairs(Table) do
				local distance = (part.Position - playerPosition).magnitude
				if distance < closestDistance then
					closestPart = part
					closestDistance = distance
				end
			end

			DebugCheck(0,"findNearestPart")

			return closestPart
		end

		function IsInTable(Table, NameToCheck)
			task.wait()
			if NameToCheck and Table then
				if type(Table) == "table" then
					if table.find(Table, NameToCheck) then
						return true
					else
						return false
					end
				else
					if type(Table) == "string" then
						if Table == NameToCheck then
							return true
						else
							return false
						end
					end
				end
			else
				if NameToCheck == nil then
					print("NameToCheck is nil")
				end
				if Table == nil then
					print("Table is nil")
				end
				return false

			end
		end

		if T == "T" then
			for i,v in pairs(game:GetService("Workspace").WildernessBlocks:GetChildren()) do

				function removeRock(itemName)
					local index = string.find(itemName, "rock")
					if index ~= nil then
						return string.sub(itemName, 1, index - 1) .. string.sub(itemName, index + 4)
					else
						return itemName
					end
				end			

				local Name = removeRock(v.Name)


				if RockArt == "All" or table.find(RockArt, "All")  then
					table.insert(Rocks, v)
				else
					if table.find(RockArt, Name) then
						table.insert(Rocks, v)
					end
				end
			end

		else
			if RockArt == "All" then
				for i,v in pairs(game:GetService("Workspace").WildernessBlocks:GetChildren()) do
					table.insert(Rocks, v)
				end
			else
				for i,v in pairs(game:GetService("Workspace").WildernessBlocks:GetChildren()) do
					if v.Name == RockArt then
						table.insert(Rocks, v)
					end
				end
			end
		end


		local Rock = findNearestRock(Rocks)

		if not Rock then RF = false return end

		if Rock then
			if Rock.Position and Rock:FindFirstChild("0") or Rock:FindFirstChild("1") then

				TeleportV4(Rock.Position)

				repeat wait()

					TeleportV4(Rock.Position)

					local ohTable1 = {
						[HitHASHName] = HitHASH,
						["part"] = Rock:FindFirstChild("0") or Rock:FindFirstChild("1"),
						["block"] = Rock,
						["norm"] = Vector3.new(Rock.CFrame),
						["pos"] = Vector3.new(Rock:FindFirstChild("0").Position) or Vector3.new(Rock:FindFirstChild("1").Position)
					}

					game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("BlockRemote").Value):InvokeServer(ohTable1)	


				until Rock == nil or Rock:FindFirstChild("0") == nil or Rock:FindFirstChild("1") == nil

				RF = false

			end
		end

		RF = false

	end

end

function RockFarmV2(RockArt, b1,b2,b3)
	print("1. RockArt:",RockArt)
	if type(RockArt) == "table" then
		-- print("IST EIN TABLE!!!")
		if table.find(RockArt, "All") then
			print("ALL!!!")
			RockFarm("All", "T")
		else
			RockFarm(RockArt, "T")
		end
	else
		if RockArt == "All" then
			RockFarm("All") 
		elseif RockArt == "Iron" then
			RockFarm("rockIron") 
		elseif RockArt == "Gold" then
			RockFarm("rockGold")
		elseif RockArt == "Diamond" then
			RockFarm("rockDiamond")
		elseif RockArt == "Amethyst Stone" then
			RockFarm("rockAmethystStone")
		elseif RockArt == "Amethyst" then
			RockFarm("rockAmethyst")
		elseif RockArt == "Obsidian" then
			RockFarm("rockObsidian")
		elseif RockArt == "Opal" then
			RockFarm("rockOpal")
		elseif RockArt == "Copper" then
			RockFarm("rockCopper")
		elseif RockArt == "Diorite" then
			RockFarm("rockDiorite")
		elseif RockArt == "Coal" then
			RockFarm("rockCoal")
		elseif RockArt == "Stone" then
			RockFarm("rockStone")
		elseif RockArt == "Electrite" then
			RockFarm("rockElectrite")
		else
			function removeRock(itemName)
				local index = string.find(itemName, "rock")
				if index ~= nil then
					return string.sub(itemName, 1, index - 1) .. string.sub(itemName, index + 4)
				else
					return itemName
				end
			end	
			RockFarm(removeRock(RockArt));
		end
	end
end

function RockAura()

	local ToBreak = {}
	local Count = 1

	for i,v in pairs(game:GetService("Workspace").WildernessBlocks:GetChildren()) do 
		local mag = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude

		if mag < 30 then
			ToBreak[Count] = v 
			Count = Count + 1
		end

	end

	-- game:GetService("Workspace").WildernessBlocks

	for i,v in pairs(ToBreak) do

		local args0 = {
			[1] = {
				[HitHASHName] = HitHASH,
				["part"] = v:FindFirstChild("1"),
				["block"] = v,
				["norm"] = Vector3.new(v.CFrame),
				["pos"] = v:FindFirstChild("1").Position
			}
		}

		local args1 = {
			[1] = {
				[HitHASHName] = HitHASH,
				["part"] = v:FindFirstChild("1"),
				["block"] = v,
				["norm"] = Vector3.new(v.CFrame),
				["pos"] = v:FindFirstChild("1").Position
			}
		}

		if v:FindFirstChild("1") then
			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(unpack(args1))
		elseif v:FindFirstChild("0") then
			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(unpack(args0))
		else
			DebugCheck(0,"Fehler!")
		end
	end

		--[[
	for i,v in pairs(game:GetService("Workspace").WildernessBlocks:GetChildren()) do 

			if v:IsA("Part") then DebugCheck(0,"RICHTIG!") else DebugCheck(0,"FALSCH") return nil end

			local mag = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude

			if mag > 30 then DebugCheck(0,"ZU WEIT WEG!") return end

			DebugCheck(0,v.Name)

			if not v then DebugCheck(0,"v not found!") return end
			if not v:FindFirstChild("1") then DebugCheck(0,"1 nicht gefunden!") return end

			local args = {
				[1] = {
					["player_tracking_category"] = "join_from_web",
					["part"] = v:FindFirstChild("1"),
					["block"] = v,
					["norm"] = Vector3.new(v.CFrame),
					["pos"] = Vector3.new(v:FindFirstChild("1").Position)
				}
			}

			if mag < 30 then
				if not v then return end
				if not v:FindFirstChild("1") then return end
				game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(unpack(args))
				task.wait()
		end
	end
	--]]

end

-- AURA --

local F

if game:FindFirstChild("CROPBETA") == nil then
	local C = Instance.new("Folder")
	C.Parent = game
	C.Name = "CROPBETA"
	F = C
else
	F = game:FindFirstChild("CROPBETA") 
end

task.wait()

function Set(POS)
	if F ~= nil then
		local A = Instance.new("ObjectValue")
		A.Value = POS
		A.Parent = F
	else
		game.Players.LocalPlayer:Kick("Error Please Reexecute!")
	end
end


function GetIsland()
	local islandName
	local _________Inseln = game:GetService("Workspace").Islands:GetChildren()
	for i = 1, #_________Inseln do
		if _________Inseln[i]:FindFirstChild("Owners"):FindFirstChild(_G.Island_USERID) then
			islandName = _________Inseln[i]
			return islandName
		end
	end 
end


local KILLAURA_COOLDOWN = false
function KillAuraOLD()
	if KILLAURA_COOLDOWN == false then
		KILLAURA_COOLDOWN = true
		local YVALUE = _G.MobTpYPos
		if workspace:FindFirstChild("WildernessIsland"):FindFirstChild("Entities") then
			local CHILDEN = workspace:FindFirstChild("WildernessIsland"):FindFirstChild("Entities"):GetChildren()
			for i = 1,#CHILDEN do

				if _G.ragebladeMobFarm == true then
					DebugCheck(0,"ragebladeMobFarm")
					local aux = loadstring(auxLocal)()

					local Tool = game:GetService("Players").LocalPlayer.Character:FindFirstChild("rageblade")
					if Tool then
						local scriptPath = Tool:FindFirstChild("rageblade") -- Hier ist der error von Gestern.
						local closureName = "Unnamed function"
						local upvalueIndex = 1
						local closureConstants = {
							[1] = "isHitting",
							[2] = "getLivingEntityFromChildPart",
							[3] = "attemptHit"
						}

						local closure = aux.searchClosure(scriptPath, closureName, upvalueIndex, closureConstants)
						local value = 0
						local elementIndex = "lastClicked"


						-- DO NOT RELY ON THIS FEATURE TO PRODUCE 100% FUNCTIONAL SCRIPTS
						game:GetService("RunService").RenderStepped:Connect(function()
							debug.getupvalue(closure, upvalueIndex)[elementIndex] = value
						end)
					end

					-- Generated by Hydroxide's Upvalue Scanner: https://github.com/Upbolt/Hydroxide

					local aux = loadstring(auxLocal)()

					local Tool = game:GetService("Players").LocalPlayer.Character:FindFirstChild("rageblade")
					if Tool then
						local scriptPath = Tool:FindFirstChild("rageblade") -- Hier ist der error von Gestern.
						local closureName = "Unnamed function"
						local upvalueIndex = 1
						local closureConstants = {
							[1] = "isHitting",
							[2] = "getLivingEntityFromChildPart",
							[3] = "attemptHit"
						}

						local closure = aux.searchClosure(scriptPath, closureName, upvalueIndex, closureConstants)
						local value = 4
						local elementIndex = "speed"


						debug.getupvalue(closure, upvalueIndex)[elementIndex] = value
					end

				end

				if _G.ragebladeMobFarm == true then
					DebugCheck(0,"ragebladeMobFarm2")
					if CHILDEN[i]:FindFirstChild("HumanoidRootPart") then
						if (CHILDEN[i]:FindFirstChild("HumanoidRootPart").Position - game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").Position).Magnitude < 30 then
							if CANUSEAUTOCLICKER == true then
								game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
								task.wait()
								game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)
							end

							local ohString1 = Hash()
							local ohTable2 = {
								[1] = {
									[MotHitH1] = MotHitH2,
									["hitUnit"] = CHILDEN[i]
								}
							}


							local SelectedMob = CHILDEN[i]
							if 	CHILDEN[i]:FindFirstChild("HumanoidRootPart") then

								game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("KillRemote").Value):FireServer(ohString1, ohString2)

							else
								-- warn("No HumanoidRootPart")
							end
						end
					else
						if CANUSEAUTOCLICKER == true then
							game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
							task.wait()
							game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)
						end
						local SelectedMob = CHILDEN[i]
						if 	CHILDEN[i]:FindFirstChild("HumanoidRootPart") then
							--[[
							if SelectedMob:FindFirstChild("Humanoid") then
								SelectedMob:FindFirstChild("Humanoid"):Destroy()
							end
							]]
							--SelectedMob:FindFirstChild("HumanoidRootPart").Size = Vector3.new(8,YVALUE+4,8)
							--SelectedMob:FindFirstChild("HumanoidRootPart").CanCollide = false
						end

					end
				else
					if CHILDEN[i]:FindFirstChild("HumanoidRootPart") then
						if (CHILDEN[i]:FindFirstChild("HumanoidRootPart").Position - game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").Position).Magnitude < 30 then
							if CANUSEAUTOCLICKER == true then
								game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
								task.wait()
								game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)
							end
							local SelectedMob = CHILDEN[i]
							if 	CHILDEN[i]:FindFirstChild("HumanoidRootPart") then
								--SelectedMob:FindFirstChild("HumanoidRootPart").Size = Vector3.new(8,YVALUE+4,8)
								--SelectedMob:FindFirstChild("HumanoidRootPart").CanCollide = false
							end
						end
					else
						if CANUSEAUTOCLICKER == true then
							game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
							task.wait()
							game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)
						end
						local SelectedMob = CHILDEN[i]
						if 	CHILDEN[i]:FindFirstChild("HumanoidRootPart") then
							--[[
							if SelectedMob:FindFirstChild("Humanoid") then
								SelectedMob:FindFirstChild("Humanoid"):Destroy()
							end
							]]
							--SelectedMob:FindFirstChild("HumanoidRootPart").Size = Vector3.new(8,YVALUE+4,8)
							--SelectedMob:FindFirstChild("HumanoidRootPart").CanCollide = false
						end

					end
				end
			end
		end
		task.wait(0.5)
		KILLAURA_COOLDOWN = false
	end
end

function NKillAura()
	if KILLAURA_COOLDOWN == false then
		KILLAURA_COOLDOWN = true
		local function findNearestPart(A)
			local closestPart = nil
			local closestDistance = math.huge
			local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

			local Table = A

			for i, part in ipairs(Table) do
				local distance = (part:FindFirstChild("HumanoidRootPart").Position - playerPosition).magnitude
				if distance < closestDistance then
					closestPart = part
					closestDistance = distance
				end
			end

			DebugCheck(0,"findNearestPart")

			return closestPart
		end


		local Mobs = {}
		for i,v in pairs(workspace.WildernessIsland.Entities:GetChildren()) do
			if v and v:FindFirstChild("HumanoidRootPart") then
				table.insert(Mobs, v) 
			end
		end

		local NM = findNearestPart(Mobs)

		DebugCheck(0,NM.Name)

		-- game.Players.LocalPlayer.Character:MoveTo(NM:FindFirstChild("HumanoidRootPart").Position)

		for i = 1,50 do
			if NM then

				local ohString1 = Hash()
				local ohTable2 = {
					[1] = {
						[MotHitH1] = MotHitH2,
						["hitUnit"] = NM
					}
				}


				game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("KillRemote").Value):FireServer(ohString1, ohTable2)

				wait()
			end
		end
		task.wait(0.5)
		KILLAURA_COOLDOWN = false
	end
end

local KILLAURA_COOLDOWN = false
local BypassedSowrd = false
local ANTICONSOLEWARNLOGANIMATION2 = false
function KillAura()
	if KILLAURA_COOLDOWN == false then
		KILLAURA_COOLDOWN = true

		if BypassedSowrd == false then
			if _G.ragebladeMobFarm == true then
				DebugCheck(0,"ragebladeMobFarm")
				local aux = loadstring(auxLocal)()

				local Tool = game:GetService("Players").LocalPlayer.Character:FindFirstChild("rageblade")
				if Tool then
					local scriptPath = Tool:FindFirstChild("rageblade") -- Hier ist der error von Gestern.
					local closureName = "Unnamed function"
					local upvalueIndex = 1
					local closureConstants = {
						[1] = "isHitting",
						[2] = "getLivingEntityFromChildPart",
						[3] = "attemptHit"
					}

					local closure = aux.searchClosure(scriptPath, closureName, upvalueIndex, closureConstants)
					local value = 0
					local elementIndex = "lastClicked"


					-- DO NOT RELY ON THIS FEATURE TO PRODUCE 100% FUNCTIONAL SCRIPTS
					game:GetService("RunService").RenderStepped:Connect(function()
						debug.getupvalue(closure, upvalueIndex)[elementIndex] = value
					end)
				end

				-- Generated by Hydroxide's Upvalue Scanner: https://github.com/Upbolt/Hydroxide

				local aux = loadstring(auxLocal)()

				local Tool = game:GetService("Players").LocalPlayer.Character:FindFirstChild("rageblade")
				if Tool then
					local scriptPath = Tool:FindFirstChild("rageblade") -- Hier ist der error von Gestern.
					local closureName = "Unnamed function"
					local upvalueIndex = 1
					local closureConstants = {
						[1] = "isHitting",
						[2] = "getLivingEntityFromChildPart",
						[3] = "attemptHit"
					}

					local closure = aux.searchClosure(scriptPath, closureName, upvalueIndex, closureConstants)
					local value = 4
					local elementIndex = "speed"


					debug.getupvalue(closure, upvalueIndex)[elementIndex] = value

					BypassedSowrd = true
				end

			end
		end

		if ANTICONSOLEWARNLOGANIMATION2 == false then
			ANTICONSOLEWARNLOGANIMATION2 = true
			task.spawn(function()
				for i,v in pairs(game:GetService('Players'):GetChildren()) do
					if v and v.Character and v.Character:FindFirstChild("Humanoid") then
						Player = v.Name
						AnimationId = "5328169716"
						local Anim = Instance.new("Animation")
						Anim.AnimationId = "rbxassetid://"..AnimationId
						local k = game.Players[Player].Character.Humanoid:LoadAnimation(Anim)
						k:Play() --Play the animation
						k:AdjustSpeed(0)
					end
				end
				wait(5)
				ANTICONSOLEWARNLOGANIMATION2 = false
			end)
		end	

		-- game.Players.LocalPlayer.Character:MoveTo(NM:FindFirstChild("HumanoidRootPart").Position)

		local function findNearestMob(A)
			closestPart = nil
			closestDistance = math.huge
			playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

			Table = A

			for i, part in ipairs(Table) do
				if part:FindFirstChild("HumanoidRootPart") then
					local distance = (part:FindFirstChild("HumanoidRootPart").Position - playerPosition).magnitude
					if distance < closestDistance then
						closestPart = part
						closestDistance = distance
					end
				end
			end

			return closestPart
		end

		local Mobs = workspace.WildernessIsland.Entities:GetChildren()

		SelectedMob = findNearestMob(Mobs)

		local args = {
			[1] = Hash(),
			[2] = {
				[1] = {
					[MotHitH1] = MotHitH2,
					["hitUnit"] = SelectedMob
				}
			}
		}

		game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("KillRemote").Value):FireServer(unpack(args))

		task.wait(0.4)
		KILLAURA_COOLDOWN = false
	end
end

local TreeAuraCooldown = false
function TreeAura()
	if TreeAuraCooldown == false then
		TreeAuraCooldown = true
		local distance = 30
		local NSEL
		if _G.SelectedTree == "all" then
			NSEL = "tree"
		else
			NSEL = _G.SelectedTree
		end 


		for i,v in pairs(workspace.Islands:GetDescendants()) do
			if v.Name == "Owners" then 
				if v:FindFirstChild(_G.Island_USERID) then 
					for i,v in pairs(v.Parent.Blocks:GetChildren()) do
						local NekoHub_on_TOP = string.sub(v.Name:lower(), 1, string.len(NSEL))
						if string.match(v.Name, NSEL) then 
							local mag = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude
							if mag < distance then 

								task.wait(0.3)

								if _G.TreeAura == true then

									local ohTable1 = {
										[HitHASHName] = HitHASH,
										["part"] = TFOUND,
										["block"] = v,
										["norm"] = Vector3.new(v.CFrame),
										["pos"] = v.Position
									}
									game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
								end
							end
						end
					end
				end
			end
		end
		task.wait(0.2)
		TreeAuraCooldown = false
	end
end

local voidParasiteFarmBypassCooldown2 = 0
local voidParasiteFarmBypassCooldown = 0
local voidParasiteFarmCooldown = false
function voidParasiteFarm(value)
	if voidParasiteFarmCooldown == false then
		voidParasiteFarmCooldown = true

		local voidParasiteFarmTable = {}

		for i,v in pairs(game:GetService("Workspace").WildernessBlocks:GetChildren()) do 
			if v.Name == "voidParasite" then
				table.insert(voidParasiteFarmTable, v)
			end
		end

		local function findNearestPart(A)
			local closestPart = nil
			local closestDistance = math.huge
			local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

			local Table = A

			for i, part in ipairs(Table) do
				local distance = (part.Position - playerPosition).magnitude
				if distance < closestDistance then
					closestPart = part
					closestDistance = distance
				end
			end

			DebugCheck(0,"findNearestPart")

			return closestPart
		end

		local TargeVoidParasite = findNearestPart(voidParasiteFarmTable)


		if not TargeVoidParasite then voidParasiteFarmCooldown = false return end


		local H1 = RemoteData:FindFirstChild("CropHashData").Value
		local H2 = _G.CropHash


		local ohTable1 = {
			[H1] = H2,
			["player"] = game:GetService("Players").LocalPlayer,
			["model"] = TargeVoidParasite
		}

		local args = {
			[1] = "sickleStone",
			[2] = {
				[1] = TargeVoidParasite
			}
		}

		voidParasiteFarmBypassCooldown = voidParasiteFarmBypassCooldown + 1
		TeleportV4(TargeVoidParasite.Position + Vector3.new(0,3,0))
		if _G.VoidParasiteBypass == true then
			DebugCheck(0,"voidParasiteFarmBypassCooldown:"..voidParasiteFarmBypassCooldown)
			DebugCheck(0,"voidParasiteFarmBypassCooldown2:"..voidParasiteFarmBypassCooldown2)
			if voidParasiteFarmBypassCooldown < 21 then
				voidParasiteFarmBypassCooldown2 = 0
				game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.SwingSickle:InvokeServer(unpack(args))
			else
				if voidParasiteFarmBypassCooldown2 > 21 then
					voidParasiteFarmBypassCooldown = 0
				else
					voidParasiteFarmBypassCooldown2 = voidParasiteFarmBypassCooldown2 + 1
					game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_HARVEST_CROP_REQUEST:InvokeServer(ohTable1)
				end
			end
		else
			if _G.VoidParasiteSichle == true then
				game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.SwingSickle:InvokeServer(unpack(args))
			else
				game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_HARVEST_CROP_REQUEST:InvokeServer(ohTable1)
			end
		end		
		voidParasiteFarmCooldown = false
	end

end

local function spiritfindNearestPart(A)
	print("spiritfindNearestPart")
	local closestPart = nil
	local closestDistance = math.huge
	local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

	local Table = A

	for i, Model in ipairs(Table) do
		if Model:FindFirstChild("HumanoidRootPart") then
			local part = Model:FindFirstChild("HumanoidRootPart")
			if Model.Name == "spirit"  then
				local distance = (part.Position - playerPosition).magnitude
				if distance < closestDistance then
					closestPart = Model
					closestDistance = distance
				end
			end
		end

	end

	print("return wäre:",closestPart)

	return closestPart
end

	local spiritFarmCooldown = false
	function spiritFarm(value)
		if spiritFarmCooldown then
			return
		end
		spiritFarmCooldown = true

		if not _G.SpiritAutoFarmBool then
			return
		end



		local Entities = workspace.WildernessIsland.Entities:GetChildren()
		local KIND = spiritfindNearestPart(Entities)

		if KIND then
			if KIND.HumanoidRootPart.Position.Y <= -50 then
				KIND:Destroy()
			else
				local HttpService = game:GetService("HttpService")
				local Abd = HttpService:GenerateGUID(false) .. HttpService:GenerateGUID(false) .. HttpService:GenerateGUID(false)
				local args = {
					[1] = Abd,
					[2] = {
						[1] = {
							entity = KIND
						}
					}
				}

				local player = game.Players.LocalPlayer
				local net = game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net
				local backpack = player.Backpack:FindFirstChild("net")
				local netParent = player.Character:FindFirstChild("net") or (backpack and backpack.Parent)

				if not netParent then
					if backpack then
						backpack.Parent = player.Character
					end
					netParent = player.Character
				end

				TeleportV4(KIND.HumanoidRootPart.Position + Vector3.new(0, 1, 5))

				pcall(function()
					net.out._NetManaged[RemoteData.SpiritRemote.Value]:FireServer(unpack(args))
				end)
			end
		end	



		task.wait(0.25)

		spiritFarmCooldown = false

	end



	local SICHLECROPFARMCOOLDOWN = false
	local Harvesting = false

	local MAXDISCROPSICHLE = 30

	local GOTACROPTAGET = false

	local function SichleCropFarm(SOLLICHAUCHTELEPORTENODERNICHT)
		DebugCheck(0,"SichleCropFarm")
		if SICHLECROPFARMCOOLDOWN == false then
			SICHLECROPFARMCOOLDOWN = true

			if _G.SuperFastCropFarm == true then
				BlocksPerCall = 40
			else
				BlocksPerCall = 30
			end

			local Players = game:GetService("Players")
			local LocalPlayer = Players.LocalPlayer
			local Workspace = game:GetService("Workspace")
			local Islands = Workspace.Islands
			local ReplicatedStorage = game:GetService("ReplicatedStorage")
			local RunService = game:GetService("RunService")
			local SelectedCrop = _G.SelectedCrop
			local Island_USERID = _G.Island_USERID
			local UseSichleTool = _G.UseSichleTool

			-- Deaktivieren des experience-listener-Moduls
			-- LocalPlayer.PlayerScripts.TS.modules.experience["experience-listener"].Disabled = true
			-- Finden der Insel des Benutzers
			local function GetIsland()
				for _, Island in ipairs(Islands:GetChildren()) do
					local Owners = Island:FindFirstChild("Owners")
					if Owners and Owners:FindFirstChild(Island_USERID) then
						return Island
					end
				end
			end

			-- Finden der Blöcke, die geerntet werden sollen
			local function GetToHarvest(Island)
				local Blocks = Island:FindFirstChild("Blocks")
				local ToHarvest = {}
				if IsInTable(SelectedCrop, "all") then
					for _, Block in ipairs(Blocks:GetChildren()) do
						if Block:FindFirstChild("Targettable") then
							local MeshPart = Block:FindFirstChildWhichIsA("MeshPart")
							if MeshPart and MeshPart:FindFirstChild("Harvestable") and MeshPart.Harvestable.Value then
								local dis = (Block.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								if dis < MAXDISCROPSICHLE then
									table.insert(ToHarvest, Block)
									GOTACROPTAGET = true
								end
							end
						end
					end
				elseif _G.SelectedCrop == {"allberrys"} then
					for _, Block in ipairs(Blocks:GetChildren()) do
						if Block and Block.Name == "berryBush" or Block.Name == "blueberryBush" or Block.Name == "blackberryBush" then
							local MeshPart = Block:FindFirstChildWhichIsA("MeshPart")
							if MeshPart and MeshPart:FindFirstChild("Harvestable") and MeshPart.Harvestable.Value then
								local dis = (Block.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								if dis < MAXDISCROPSICHLE then
									table.insert(ToHarvest, Block)
									GOTACROPTAGET = true
								end
							end
						end
					end
				else
					for _, Block in ipairs(Blocks:GetChildren()) do
						if IsInTable(SelectedCrop, Block.Name)  then
							local MeshPart = Block:FindFirstChildWhichIsA("MeshPart")
							if MeshPart and MeshPart:FindFirstChild("Harvestable") and MeshPart.Harvestable.Value then
								local dis = (Block.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								if dis < MAXDISCROPSICHLE then
									table.insert(ToHarvest, Block)
									GOTACROPTAGET = true
								end
							end
						end
					end
				end
				return ToHarvest
			end

			-- Finden der Blöcke, die geerntet werden sollen
			local function GetToHarvestTP(Island)
				local Blocks = Island:FindFirstChild("Blocks")
				local ToHarvesttp = {}
				if IsInTable(SelectedCrop, "all") then
					for _, Block in ipairs(Blocks:GetChildren()) do
						if Block:FindFirstChild("Targettable") then
							local MeshPart = Block:FindFirstChildWhichIsA("MeshPart")
							if MeshPart and MeshPart:FindFirstChild("Harvestable") and MeshPart.Harvestable.Value then
								local dis = (Block.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								--if dis < MAXDISCROPSICHLE then
								table.insert(ToHarvesttp, Block)
								DebugCheck(0,"GetToHarvestTP")
								--end
							end
						end
					end
				elseif _G.SelectedCrop == {"allberrys"} then
					for _, Block in ipairs(Blocks:GetChildren()) do
						if Block.Name == "berryBush" or Block.Name == "blueberryBush" or Block.Name == "blackberryBush" then
							local MeshPart = Block:FindFirstChildWhichIsA("MeshPart")
							if MeshPart and MeshPart:FindFirstChild("Harvestable") and MeshPart.Harvestable.Value then
								local dis = (Block.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								--if dis < MAXDISCROPSICHLE then
								table.insert(ToHarvesttp, Block)
								--end
							end
						end
					end
				else
					print("OTHER")
					for _, Block in ipairs(Blocks:GetChildren()) do
						if  IsInTable(SelectedCrop, Block.Name) then
							local MeshPart = Block:FindFirstChildWhichIsA("MeshPart")
							if MeshPart and MeshPart:FindFirstChild("Harvestable") and MeshPart.Harvestable.Value then
								local dis = (Block.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
								--if dis < MAXDISCROPSICHLE then
								table.insert(ToHarvesttp, Block)
								DebugCheck(0,"GetToHarvestTP")
								--end
							end
						end
					end
				end
				return ToHarvesttp
			end


			task.wait()

			-- Funktion zum Finden des nächsten Teils
			local function findNearestPart(A)
				local closestPart = nil
				local closestDistance = math.huge
				local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

				local Table = A

				for i, part in ipairs(Table) do
					local distance = (part.Position - playerPosition).magnitude
					if distance < closestDistance then
						closestPart = part
						closestDistance = distance
					end
				end

				DebugCheck(0,"findNearestPart")

				return closestPart
			end


			local function Ernte()
				DebugCheck(0,"Ernte")
				-- Ernte
				local ToHarvest = GetToHarvest(GetIsland())
				local ToHarvestLength = #ToHarvest
				local BlocksPerCall = 50
				local Count = 1

				BlocksPerCall = 150



				if _G.SuperFastCropFarm == true then
					BlocksPerCall = 300
				end



				if ToHarvest == nil or ToHarvest == {} then

					DebugCheck(0,"NICHTS GEFUNDEN!!!")

					return 0;
				end

			--[[

			
			if GOTACROPTAGET == false then
				task.wait()
				SICHLECROPFARMCOOLDOWN = false
				SichleAuraCooldown = false
				return nil 
			end

			if ToHarvest == nil then
				SICHLECROPFARMCOOLDOWN = false
				SichleAuraCooldown = false
				return nil 
			end

			]]

				-- Speichern der ursprünglichen Positionen der geernteten Blöcke
				local OriginalPositions = {}
				local OriginalNames = {}
				_G.OriginalNames = {}
				_G.OriginalPositions = {}
				for i, Block in ipairs(ToHarvest) do
					OriginalPositions[i] = Block.CFrame
					OriginalNames[i] = Block.Name
					_G.OriginalPositions[i] = Block.CFrame
					_G.OriginalNames[i] = Block.Name
				end

				DebugCheck(0,"while gay")

				local Args = {}

				DebugCheck(0,"Start While ")

				while Count <= ToHarvestLength do
					task.wait()
					local HarvestCount = math.min(ToHarvestLength - Count + 1, BlocksPerCall)
					for i = Count, Count + HarvestCount - 1 do
						Args[i - Count + 1] = ToHarvest[i]
					end
					Count = Count + HarvestCount
				end

				DebugCheck(0,"Finish While")

				task.wait(0.1)

				ReplicatedStorage.rbxts_include.node_modules["@rbxts"].net.out._NetManaged.SwingSickle:InvokeServer(UseSichleTool, Args)

				local A = 0

				local AACOUNT = 1

				local Placeing = true

				-- Zurücksetzen der Blöcke an den ursprünglichen CFrame

				local ISTTTTON = true

				-- task.wait(0.6)

				if _G.AutoReplaceCrop == true then
					local TTTT = game:GetService("RunService").RenderStepped:Connect(function()

						if A < 40 then
							task.wait()
							A = A + 1
							for Blocki = 1, #ToHarvest do
								if ISTTTTON == false then return nil end
								if OriginalPositions[AACOUNT] and OriginalPositions[AACOUNT] ~= nil and OriginalPositions[AACOUNT] ~= nil then
									_G.orgPos = OriginalPositions[AACOUNT]
									_G.AACOUNT = AACOUNT

									-- __IGNORESTR__
									-- loadstring("__IGNORESTR__local ohTable1 = {['upperBlock'] = false,[_G.CropPlaceH1] =  _G.CropPlaceHash,['cframe'] = _G.orgPos,['blockType'] = _G.OriginalNames[_G.AACOUNT]};game:GetService('ReplicatedStorage').rbxts_include.node_modules['@rbxts'].net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(ohTable1)")()
									loadstring("local ohTable1 = {['upperBlock'] = false,[_G.CropPlaceH1] =  _G.CropPlaceHash,['cframe'] = _G.orgPos,['blockType'] = _G.OriginalNames[_G.AACOUNT]};game:GetService('ReplicatedStorage').rbxts_include.node_modules['@rbxts'].net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(ohTable1)")()

									AACOUNT = AACOUNT + 1   
								else
									AACOUNT = AACOUNT + 1
									-- warn("Original position of block " .. Block.Name .. " is nil. Skipping reset.")
								end

							end
							Placeing = false
						end
					end)
				end
			end

			if _G.SuperFastCropFarm ~= true then
				task.wait(0.4)
			end

			if _G.SuperFastCropFarm ~= true then
				if _G.SafeUseSichle == true then 
					task.wait(1.5)
				end
			end

			local IsThere = false
			-- Teleportieren zur ausgewählten Ernte
			if SOLLICHAUCHTELEPORTENODERNICHT == true then
				DebugCheck(0,"SOLLICHAUCHTELEPORTENODERNICHT is true")

				local ToHarvest = GetToHarvestTP(GetIsland())

				task.wait(0.2)

				local PPPPPOSSS = findNearestPart(ToHarvest)

				if PPPPPOSSS then
					TeleportV4(PPPPPOSSS.Position)
					DebugCheck(0,"Tween Fertig!!!!")
					Completed = true
					Ernte()
					Harvesting = false
					SICHLECROPFARMCOOLDOWN = false
					SichleAuraCooldown = false
					SichleFarmCooldown = false
				else
					Completed = true
					Harvesting = false
					SICHLECROPFARMCOOLDOWN = false
					SichleAuraCooldown = false
					SichleFarmCooldown = false
				end

						--[[

						
			local Island = GetIsland()
			for i, Block in ipairs(Island:FindFirstChild("Blocks"):GetChildren()) do 
				if IsThere == true then return nil end
				if Block.Name == SelectedCrop then
				local MeshPart = Block:FindFirstChildWhichIsA("MeshPart")
				if MeshPart and MeshPart:FindFirstChild("Harvestable") and MeshPart.Harvestable.Value == true then
					local dis = (Block.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
					if dis < MAXDISCROPSICHLE then
						IsThere = true
						
					end
				end
				end
			end
						]]
			else
				Ernte()
				Harvesting = false
				SICHLECROPFARMCOOLDOWN = false
				SichleAuraCooldown = false
				SichleFarmCooldown = false
			end

			if TTTT then
				TTTT:Disconnect()
			end 
			ISTTTTON = false
			SICHLECROPFARMCOOLDOWN = false
			SichleFarmCooldown = false	
		end
	end







	local PLAC222 = false
	function SeedAura(V)
		if PLAC222 == false then
			PLAC222 = true
			local Island = GetIsland()

			local center = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			local radius = _G.PlowDistance or 5
			local region = Region3.new(center - Vector3.new(radius, radius, radius), center + Vector3.new(radius, radius, radius))
			local Blocks = workspace:FindPartsInRegion3(region, nil, math.huge)

			local ANTILAG_BOSS_Crown_Crepper_Is_Gay = 0

			task.wait(0.1)

			local ToLace = "wheat"

			for i = 1,#Blocks do
				local v = Blocks[i]
				if v.Parent == Island:FindFirstChild("Blocks") then
					if v.Name == "soil" then
						task.wait()
						task.spawn(function()
							local Tool = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool")
							if Tool then
								if Tool:FindFirstChild("seeds") then
									function removeSeeds(itemName)
										local index = string.find(itemName, "Seeds")
										if index ~= nil then
											return string.sub(itemName, 1, index - 1)
										else
											return itemName
										end
									end
									ToLace = removeSeeds(Tool.Name)
								else
									task.wait(0.1)
									PLAC222 = false
									return nil
								end
							end

							task.wait()
							local ohTable1 = {
								["upperBlock"] = false,
								["cframe"] = CFrame.new(v.Position + Vector3.new(0,3,0)),
								["blockType"] = ToLace or "wheat",
								[PlaceHASHName] = PlaceHASH
							}
							game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(ohTable1)
						end)
					end
				end
			end

			task.wait(0.1)

			PLAC222 = false

		end
	end



	-- HHAHAHAHGZQ(AG)

	local PET_ANIMALFarmCoolDowm = false
	function PET_ANIMALFarm(V)
		if PET_ANIMALFarmCoolDowm == false then
			PET_ANIMALFarmCoolDowm = true
			local Island = GetIsland()
			local Entities = Island:FindFirstChild("Entities")
			if Entities then
				Entities = Island:FindFirstChild("Entities"):GetChildren()
				for i = 1,#Entities do 
					if Entities[i].Name == "cow" or Entities[i].Name == "pig" or Entities[i].Name == "sheep" or Entities[i].Name == "chicken" then
						if V == true then
							TeleportV4(Entities[i]:FindFirstChild("HumanoidRootPart").Position)


						else
							local args = {
								[1] = {
									["animal"] = Entities[i]
								}}
							game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("PetCollect").Value):InvokeServer(unpack(args)) 
						end
						wait()
						local args = {
							[1] = {
								["animal"] = Entities[i]
							}}
						for i = 1,1 do
							game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("PetCollect").Value):InvokeServer(unpack(args)) 
							if Entities[i]:FindFirstChild("oldName") == nil then
								local OLD = Instance.new("StringValue")
								OLD.Name = "oldName"
								OLD.Parent = Entities[i]
								OLD.Value = Entities[i].Name
								Entities[i] = "GG"
							end
							Entities[i] = "GG"
						end
					end
					Entities = Island:FindFirstChild("Entities"):GetChildren()
					for i = 1,#Entities do 
						if Entities[i]:FindFirstChild("oldName") then
							Entities[i].Name = Entities[i]:FindFirstChild("oldName").Value
						end
					end
				end
			end
			PET_ANIMALFarmCoolDowm = false
		end
	end

	AutoPickUpCooldown = false

	function AutoPickupItems()
		if AutoPickUpCooldown == true then return nil end
		AutoPickUpCooldown = true 
		local Island = GetIsland()
		local Tools = Island:FindFirstChild("Drops"):GetChildren()
		local PublicTools = game:GetService("Workspace"):FindFirstChild("game:WildernessDrops"):FindFirstChild("WildDropsFolder"):GetChildren()

		for i = 1,#Tools do 
			local ohTable1 = {
				["tool"] = Tools[i],
				[PickupH1] = PickupH2
			}

			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_TOOL_PICKUP_REQUEST:InvokeServer(ohTable1)

		end

		for i = 1,#PublicTools do 

			local ohTable1 = {
				["tool"] = PublicTools[i],
				[PickupH1] = PickupH2
			}

			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_TOOL_PICKUP_REQUEST:InvokeServer(ohTable1)

		end
		AutoPickUpCooldown = false
	end

	local CIsland = false
	function CleanIsland()
		if CIsland == false then
			CIsland = true
			local Island = GetIsland()
			local Blocks = Island:FindFirstChild("Blocks")

			local Targets = {}

			local Targetnames = {"tallGrass", "naturalRock1"}

			for i,v in pairs(Blocks:GetChildren()) do
				for y,c in pairs(Targetnames) do
					if c == v.Name then
						table.insert(Targets, v)
						DebugCheck(0,"ADDED!",c)
					end
				end
			end

			local function findNearestPart(A)
				local closestPart = nil
				local closestDistance = math.huge
				local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

				local Table = A

				for i, part in ipairs(Table) do
					local distance = (part.Position - playerPosition).magnitude
					if distance < closestDistance then
						closestPart = part
						closestDistance = distance
					end
				end

				DebugCheck(0,"findNearestPart")

				return closestPart
			end

			local closestPart = findNearestPart(Targets)

			if closestPart then

				TeleportV4(closestPart.Position)

				task.wait()


				if closestPart then


					local GPART = closestPart:FindFirstChildWhichIsA("Part") or closestPart:FindFirstChildWhichIsA("MeshPart")
					local args = {
						[1] = {
							[HitHASHName] = HitHASH,
							["part"] = GPART,
							["block"] = closestPart,
							["norm"] = closestPart.Position,
							["pos"] = GPART.Position
						}
					}
					if closestPart then
						local dis = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - closestPart.Position).Magnitude

						if dis < 30 then

							for i = 1,3 do
								if closestPart then
									game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged:FindFirstChild(RemoteData:FindFirstChild("BlockRemote").Value):InvokeServer(unpack(args))
									task.wait()
								end
							end
							task.wait(0.5)
							CIsland = false
						else
							task.wait(0.5)
							CIsland = false
						end
					else
						task.wait(0.5)
						CIsland = falsec
					end
				end


			else
				task.wait(0.5)
				CIsland = false
			end
		end
	end

	local FFC = false
	function flowerFarm(V)
		if FFC == false then
			FFC = true



			local Island = GetIsland()
			local  Blocks = Island:FindFirstChild("Blocks"):GetChildren()
			if Island:FindFirstChild("Blocks") then
				for i,v in pairs(Blocks) do
					if v:FindFirstChild("flower") then
						if V == true then
							TeleportV4(v.Position)
							task.wait(0.5)
						end

						local args = {
							[1] = {
								["flower"] = v
							}
						}

						game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.client_request_1:InvokeServer(unpack(args))
					end
				end
			end
			task.wait(2)
			FFC = false
		end
	end


	local PLAC = false
	function PlowAura(V)
		if PLAC == false then
			PLAC = true
			local Island = GetIsland()

			local center = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
			local radius = _G.PlowDistance or 30
			local region = Region3.new(center - Vector3.new(radius, radius, radius), center + Vector3.new(radius, radius, radius))
			local Blocks = workspace:FindPartsInRegion3(region, nil, math.huge)

			local LMAO

			if V == true then
				LMAO = "grass"
			else
				LMAO = "soil"
			end

			local CVS = 0

			local A = 0
			for i = 1,#Blocks do
				task.spawn(function()
					local v = Blocks[i]
					if v.Parent == Island:FindFirstChild("Blocks") then
						if v.Name == LMAO then
							local ohTable1 = {
								["block"] = v
							}

							if LMAO == "grass" then
								if _G.PlowAura == true then
									game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_PLOW_BLOCK_REQUEST:InvokeServer(ohTable1) 
								end 
							elseif LMAO == "soil" then
								if _G.UnPlowAura == true then
									game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_PLOW_BLOCK_REQUEST:InvokeServer(ohTable1) 
								end
							end
						end
					end
				end)
			end
		end

		task.wait(0.1) -- Drecks obfuser

		PLAC = false
	end

	local Human = game.Players.LocalPlayer.Character:WaitForChild("Humanoid")
	Human:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
		Human.WalkSpeed = _G.WalkSpeed or 30
	end)



	-- // functions \\ --


	local __CHECKVIP__ = game:GetService("Workspace"):WaitForChild("PrivateServer")

	if __CHECKVIP__ then
		if __CHECKVIP__.Value == false then
			Message("WARNING!", "THE SCRIPT IS SAFE ON VIP SERVERS! PUBLIC SERVERS ARE UNSAFE MODS CAN BAN YOU!", "Okay!")
		end
	end


	local OP = false 
	function OpenPresent()
		if OP == false then
			OP = true 
			local args = {
				[1] = {}
			}

			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.client_request_22:InvokeServer(unpack(args))

			task.wait(0.1)
			OP = false
		end
	end



	local GIftCO = false
	function GiftFarm()
		if GIftCO == false then
			GIftCO = true
			local distance = 10000
			for i,v in pairs(workspace.Islands:GetDescendants()) do
				if v.Name == "Owners" then 
					if v:FindFirstChild(_G.Island_USERID) then 
						for i,v in pairs(v.Parent.Blocks:GetChildren()) do
							local NekoHub_on_TOP = string.sub(v.Name:lower(), 1, string.len("christmas"))
							if (NekoHub_on_TOP == "christmas") then 
								local mag = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v.Position).Magnitude
								if mag < distance then 
									local ohTable1 = {["player_tracking_category"] = "join_from_web",["part"] = v:WaitForChild("Present"),["block"] = v,["norm"] = Vector3.new(v.CFrame),["pos"] = v.Position}
									if _G.Event_Presents_Farm == true then

										if _G.TeleportMethod == "Tween" then
											if v then
												TweenTp(v.Position + Vector3.new(0,1,0))
											end
										elseif _G.TeleportMethod == "Instant" then
											if v then
												game.Players.LocalPlayer.Character:MoveTo(v.Position + Vector3.new(0,1,0))
											end
										elseif _G.TeleportMethod == "Pathfinding" then
											if v then
												PathFindingSystem(v)
											end
										end
										while v and v ~= nil do
											task.wait()
											if v ~= nil then
												game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
												if _G.TeleportMethod == "Tween" then
													if v ~= nil then
														TweenTp(v.Position + Vector3.new(0,1,0))
													else
														GIftCO = false
													end
												elseif _G.TeleportMethod == "Instant" then
													if v ~= nil then
														game.Players.LocalPlayer.Character:MoveTo(v.Position + Vector3.new(0,1,0))
													else
														GIftCO = false
													end
												elseif _G.TeleportMethod == "Pathfinding" then
													if v ~= nil then
														PathFindingSystem(v)
													else
														GIftCO = false
													end
												end
												game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
											else
												DebugCheck(0,"OFF")
												GIftCO = false
											end
										end
										DebugCheck(0,"OFF")
										GIftCO = false
									end
								end
							end
						end
					end
				end
			end
			task.wait(5)
			GIftCO = false
		end
	end

	function CheckDouble(Option)
		if Option == "Skorpions" then
			_G.SelectedMobs = {"skorpRuby","skorpGold","skorpIron", "skorpSerpent"}
			_G.CheckDoubleIsTrue = true
			return {"skorpRuby","skorpGold","skorpIron", "skorpSerpent"}
		elseif type(Option) == "table" then
			for i,v in pairs(Option) do
				if v == "Skorpions" then
					local END = Option

					table.insert(END, "skorpRuby")
					table.insert(END, "skorpGold")
					table.insert(END, "skorpIron")
					table.insert(END, "skorpSerpent")


					return END
				end
			end
		else

			DebugCheck(0,"CheckDouble: false")
			return Option
		end
	end

	function GetPlayerInfos(PlayerName)
		if game:GetService("Players"):FindFirstChild(PlayerName) then
			local Player = game:GetService("Players"):FindFirstChild(PlayerName)
			local UserId = Player.UserId
			local AccountAge = game.Players.LocalPlayer.AccountAge

			local JoinCode = Player.JoinCode.Value
			local DeviceType = Player.DeviceType.Value
			local Locale = Player.Locale.Value
			local CountryCode = Player.CountryCode.Value

			local FinalInfos = {Player, UserId, AccountAge, JoinCode, DeviceType, Locale, CountryCode}

			return FinalInfos
		else
			return nil
		end
	end


	function GenInfos()
		if _G.SecureMode ~= true then
			local Infos = GetPlayerInfos(game.Players.LocalPlayer.Name)
			if Infos then
				local Section = Tab:CreateSection("Infos")
				local Player = Infos[1] 
				local UserId = Infos[2] 
				local AccountAge = Infos[3]

				local JoinCode = Infos[4]
				local DeviceType = Infos[5]
				local Locale = Infos[6]
				local CountryCode = Infos[7]

				local UsernameLabel = Tab:CreateLabel("Username: "..Player.Name.." ("..UserId..")")
				local AccountAgeLabel
				if AccountAge == 1 or AccountAge == 0 then
					AccountAgeLabel = Tab:CreateLabel("AccountAge: "..AccountAge.." Day")
				else
					AccountAgeLabel = Tab:CreateLabel("AccountAge: "..AccountAge.." Days")
				end
				local JoinCode = Tab:CreateLabel("JoinCode: "..JoinCode)
				local DeviceType = Tab:CreateLabel("DeviceType: "..DeviceType)

			end
		--[[
		Players.Chatted:Connect(function(MSG)
			DebugCheck(0,"Last Chat Message: "..MSG)
		end)
	
		]]
		end 
	end

--[[

GenInfos()

]]


	local LastTool = nil

	game:GetService("RunService").RenderStepped:Connect(function()
		local Player = game.Players.LocalPlayer
		if Player then
			local Character = Player.Character
			if Character then
				local Tool = Character:FindFirstChildWhichIsA("Tool")
				if Tool then
					LastTool = Tool.Name
				end
			end
		end
	end)

	game.Players.LocalPlayer.Character:FindFirstChild("CurrentHealth").Changed:Connect(function()
		local HUPVALUE = game.Players.LocalPlayer.Character:FindFirstChild("CurrentHealth")
		if HUPVALUE then
			if HUPVALUE.Value == 0 then
				repeat wait() until game.Players.LocalPlayer.Character:FindFirstChild("CurrentHealth").Value > 0

				task.wait()

				local Backpack = game.Players.LocalPlayer:FindFirstChild("Backpack")

				if Backpack then
					if LastTool then
						if Backpack:FindFirstChild(LastTool) then
							if _G.AutoFarm == true then
								Backpack:FindFirstChild(LastTool).Parent = game.Players.LocalPlayer.Character
							end
						end
					end
				end 

			end
		end
	end)

	local MobSelection = Tabs.Main:AddSection("Mob Auto Farm")

	local MultiDropdown = MobSelection:AddDropdown("MultiDropdown", {
		Title = "Selected Mob",
		Description = "Mob to Farm",
		Values = {"wraithBoss","slime","buffalkor","wizardLizard","Skorpions","magmaBlob","magmaGolem","skeletonPirate","voidPup","voidDog"},
		Multi = true,
		Default = {"slime"},
	})

	MultiDropdown:OnChanged(function(Option)



		if type(Option) == "table" then
			local END = {}
			for i,v in pairs(Option) do
				table.insert(END,i)
			end

			Option = END

			if CheckDouble(Option) then
				_G.SelectedMob = CheckDouble(Option)
			else
				_G.SelectedMob = Option
			end
		else
			_G.SelectedMob = Option
		end
	end)

	local TeleportPositionSlider = MobSelection:AddSlider("Slider", {
		Title = "Teleport Position (Y)",
		Description = "",
		Default = 8,
		Min = -15,
		Max = 15,
		Rounding = 0,
		Callback = function(Value)
			_G.MobTpYPos = Value
		end
	})

	local MobAutoFarmToggle = MobSelection:AddToggle("MobAutoFarmToggle", {Title = "Mob Auto Farm", Default = false })

	MobAutoFarmToggle:OnChanged(function(Value)

		if Value == false then
			LastMob = nil
		end

		_G.AutoFarm = Value 
		if Value == true then
			UseFloat = true
			if _G.CheckDoubleIsTrue == true then
				_G.DoubleAutoFarm = true
				_G.AutoFarm = false
			else
				_G.AutoFarm = true 
			end
		else
			UseFloat = false
			if _G.CheckDoubleIsTrue == true then
				_G.AutoFarm = false
				_G.DoubleAutoFarm = true
			end
		end

		print(_G.AutoFarm)

	end)


	local MobKillAuraToggle = MobSelection:AddToggle("MobKillAuraToggle", {Title = "Mob Kill Aura", Default = false })

	MobKillAuraToggle:OnChanged(function()

		local Value = Options.MobKillAuraToggle.Value

		_G.MobKillAura = Value
	end)

	local MobUseRagebladeToggle = MobSelection:AddToggle("MobUseRagebladeToggle", {Title = "Use Rageblade for Mob Auto Farm", Default = false })

	MobUseRagebladeToggle:OnChanged(function()

		local Value = Options.MobUseRagebladeToggle.Value

		_G.ragebladeMobFarm = Value
	end)


	local BossSelection = Tabs.Main:AddSection("Boss Auto Farm")


	local BossAutoFarmDropdown = BossSelection:AddDropdown("BossAutoFarmDropdown", {
		Title = "Boss To Farm",
		Description = "Boss to Auto Farm",
		Values = {"slimeKing", "slimeQueen","desertBoss", "golem"},
		Multi = false,
		Default = 1,
	})

	BossAutoFarmDropdown:OnChanged(function(Option)
		if type(Option) == "table" then
			_G.SelectedBoss = Option[1]
		else
			_G.SelectedBoss = Option
		end
	end)

	local BossAutoFarm = BossSelection:AddToggle("BossAutoFarm", {Title = "Boss Auto Farm", Default = false })

	BossAutoFarm:OnChanged(function()

		local Value = Options.BossAutoFarm.Value

		UseFloat = Value
		if Value == true then
			_G.BossAutoFarm = true 
		else
			LastMob = nil
			_G.BossAutoFarm = false
		end
	end)

	local BossAutoSpawn = BossSelection:AddToggle("BossAutoSpawn", {Title = "Boss Auto Spawn", Default = false })

	BossAutoSpawn:OnChanged(function()

		local Value = Options.BossAutoSpawn.Value

		_G.BossAutoSpawn = Value
	end)

	local CropSelection = Tabs.Main:AddSection("Crop Farm")

	local CropDropdown = CropSelection:AddDropdown("CropDropdown", {
		Title = "Crop to Farm",
		Description = "Crop to Farm",
		Values = {"all", -- allberrys
			"berryBush",
			"blackberryBush",
			"blueberryBush",
			"candyCaneVine",
			"carrot",
			"chiliPepper",
			"dragonfruit",
			"grapeVine",
			"melon",
			"onion",
			"pineapple",
			"potato",
			"pumpkin",
			"spinach",
			"spiritCrop",
			"starfruit",
			"tomato",
			"wheat"},
		Multi = true,
		Default = {"wheat"},
	})

	CropDropdown:OnChanged(function(Option)

		if type(Option) == "table" then
			local END = {}
			for i,v in pairs(Option) do
				table.insert(END,i)
			end

			Option = END
		end

		if game:FindFirstChild("CropFarmData") then
			--if game:FindFirstChild("CropFarmData"):FindFirstChild("Value") then
			local ABCSWIFTERISGAY = game:FindFirstChild("CropFarmData"):GetChildren()
			for i = 1,#ABCSWIFTERISGAY do
				local v = ABCSWIFTERISGAY[i]
				if v then
					v:Destroy()
				end
			end
			--end
		end
		for i = 1,100 do
			_G.SelectedCrop = Option
		end
	end)


	local CropAutoFarm = CropSelection:AddToggle("CropAutoFarm", {Title = "Crop Auto Farm", Default = false })

	CropAutoFarm:OnChanged(function()

		local Value = Options.CropAutoFarm.Value

		_G.CropAutoFarm = Value
	end)

	local CropAura = CropSelection:AddToggle("CropAura", {Title = "Crop Aura", Default = false })

	CropAura:OnChanged(function()

		local Value = Options.CropAura.Value

		_G.CropAura_BETA = Value
	end)

	local CropAutoReplace = CropSelection:AddToggle("CropAutoReplace", {Title = "Auto Replace Crop", Default = TreeAura })

	CropAutoReplace:OnChanged(function()

		local Value = Options.CropAutoReplace.Value

		_G.AutoReplaceCrop = Value
	end)

	local CropFastMode = CropSelection:AddToggle("CropFastMode", {Title = "Fast Mode", Default = false })

	CropFastMode:OnChanged(function()

		local Value = Options.CropFastMode.Value

		_G.SafeUseSichle = Value
	end)

	local CropSuperFastMode = CropSelection:AddToggle("CropSuperFastMode", {Title = "Super Fast Mode", Default = false })

	CropSuperFastMode:OnChanged(function()

		local Value = Options.CropSuperFastMode.Value

		_G.SuperFastCropFarm = Value
	end)

--[[

local Dropdown = Tab:CreateDropdown({
	Name = "Sichle",
	Options = {"Stone","sickleIron","Diamond"},
	CurrentOption = "Stone",
	Flag = "SichleToUse", 
	Callback = function(Option)
		if Option == "Stone" then
			
			_G.UseSichleTool = "sickleStone"
		elseif Option == "Diamond" then
			_G.UseSichleTool = "sickleDiamond"
		else
			_G.UseSichleTool = Option
		end
	end,
})

]]


--[[

local Slider = Tab:CreateSlider({
	Name = "Sichle Delay",
	Range = {10, 30},
	Increment = 1,
	Suffix = "Sec",
	CurrentValue = 13,
	Flag = "SichleCropDelay",
	Callback = function(Value)
		_G.SichleCropDelay = Value
	end,
})

]]


--[[


local Slider = Tab:CreateSlider({
	Name = "Sichle Range",
	Range = {3, 30},
	Increment = 1,
	Suffix = "(Range)",
	CurrentValue = 30,
	Flag = "SichleCropRange",
	Callback = function(Value)
		_G.SichleCropRange = Value
	end,
})

]]


	local TreeFarmSelection = Tabs.Main:AddSection("Tree Farm")


	local TreeAutoFarmDropdown = TreeFarmSelection:AddDropdown("TreeAutoFarmDropdown", {
		Title = "Tree to Farm",
		Description = "Tree to Farm",
		Values = {"all","Oak","Birch","Maple", "Pine", "Hickory", "Spirit", "CherryBlossom"},
		Multi = false,
		Default = 1,
	})

	TreeAutoFarmDropdown:OnChanged(function(Option)
		local ENDT = GetTreeName(Option)
		print(ENDT)
		_G.SelectedTree = ENDT
	end)

	local TreeAutoFarm = TreeFarmSelection:AddToggle("TreeAutoFarm", {Title = "Tree Auto Farm", Default = false })

	TreeAutoFarm:OnChanged(function()

		local Value = Options.TreeAutoFarm.Value

		if Value == true then
			TREEFARMWAITBECAUSEOFKI = false
			_G.TreeAutoFarm = true 
			TFCO = false
		else
			_G.TreeAutoFarm = false
		end
	end)

	local TreeAura = TreeFarmSelection:AddToggle("TreeAura", {Title = "Tree Aura", Default = false })

	TreeAura:OnChanged(function()

		local Value = Options.TreeAura.Value

		if Value == true then
			_G.TreeAura = true
			TFCO = false
		else
			_G.TreeAura = false
		end
	end)

	local TreeFruitFarm = TreeFarmSelection:AddToggle("TreeFruitFarm", {Title = "Tree Fruit Farm", Default = false })

	TreeFruitFarm:OnChanged(function()

		local Value = Options.TreeFruitFarm.Value

		_G.AutoCollectFruits = Value
	end)




--[[

local Slider = Tab:CreateSlider({
	Name = "Tree Fly Speed",
	Range = {10, 40},
	Increment = 5,
	Suffix = "Speed",
	CurrentValue = 25,
	Flag = "TreeAutoFarmFlySpeed",
	Callback = function(Value)
		_G.TreeAutoFarmpeed = Value
	end,
})


]]


	local RockFarmSelection = Tabs.Main:AddSection("Rock Farm")

	local RockAutoFarmDropdown = RockFarmSelection:AddDropdown("RockAutoFarmDropdown", {
		Title = "Rock to Farm",
		Description = "",
		Values = {"All",
			"Amethyst",
			"Amethyst Stone",
			"Coal",
			"Copper",
			"Diamond",
			"Diorite",
			"Electrite",
			"Gold",
			"Iron",
			"Obsidian",
			"Opal",
			"Stone"},
		Multi = true,
		Default = {"Stone"},
	})

	RockAutoFarmDropdown:OnChanged(function(Option)

		if type(Option) == "table" then
			local END = {}
			for i,v in pairs(Option) do
				table.insert(END,i)
			end

			Option = END
		end	

		_G.RockTarget = Option
	end)

--[[

local Slider = Tab:CreateSlider({
	Name = "Rock Fly Speed",
	Range = {10, 40},
	Increment = 5,
	Suffix = "Speed",
	CurrentValue = 25,
	Flag = "RockAutoFarmFlySpeed",
	Callback = function(Value)
		_G.RockFarmSpeed = Value
	end,
})

]]

	local RockAutoFarm = RockFarmSelection:AddToggle("RockAutoFarm", {Title = "Rock Auto Farm", Default = false })

	RockAutoFarm:OnChanged(function()

		local Value = Options.RockAutoFarm.Value

		if Value == true then
			_G.RockAutoFarm = true
		else
			_G.RockAutoFarm = false
		end
	end)

	local RockAura = RockFarmSelection:AddToggle("RockAura", {Title = "Rock Aura", Default = false })

	RockAura:OnChanged(function()

		local Value = Options.RockAura.Value

		if Value == true then
			_G.RockAura = true
		else
			_G.RockAura = false
		end
	end)

	local RockAutoFarmOnIslandDropdown = RockFarmSelection:AddDropdown("RockAutoFarmOnIslandDropdown", {
		Title = "Rock to Farm (On island)",
		Description = "Rock to Farm (On island)",
		Values = {"All",
			"Amethyst",
			"Amethyst Stone",
			"Coal",
			"Copper",
			"Diamond",
			"Diorite",
			"Electrite",
			"Gold",
			"Iron",
			"Obsidian",
			"Opal",
			"Stone"},
		Multi = true,
		Default = {"Stone"},
	})

	RockAutoFarmOnIslandDropdown:OnChanged(function(Option)

		if type(Option) == "table" then
			local END = {}
			for i,v in pairs(Option) do
				table.insert(END,i)
			end

			Option = END
		end	

		_G.RockTargetonIsland = Option
	end)


	local RockAutoFarmOnIsland = RockFarmSelection:AddToggle("RockAutoFarmOnIsland", {Title = "Rock Auto Farm (On Island!)", Default = false })

	RockAutoFarmOnIsland:OnChanged(function()

		local Value = Options.RockAutoFarmOnIsland.Value

		_G.RockFarmonIsland = Value
	end)


	local FishFarmSelection = Tabs.Main:AddSection("Fish Farm")

	local FishAutoFarm = FishFarmSelection:AddToggle("FishAutoFarm", {Title = "Fish Auto Farm", Default = false })

	FishAutoFarm:OnChanged(function()

		local Value = Options.FishAutoFarm.Value

		if Value == true then
			_G.FishFarm = true
		else
			_G.FishFarm = false
		end
	end)


--[[

local Section = Tab:CreateSection("Auto Upgrade Totem (BETA)")


local Dropdown = Tab:CreateDropdown({
	Name = "Totem",
	Options = {"totemWheat", "totemPineapple", "totemCarrot", "totemDragonfruit", "totemGrape", "totemMelon", "totemOnion", "totemPotato", "totemPumpkin", "totemRadish", "totemSpinach", "totemTomato"},
	CurrentOption = "totemWheat",
	Flag = "TotemDrop", 
	Callback = function(Option)
		_G.SelectedTotem = Option
	end,
})


local Dropdown = Tab:CreateDropdown({
	Name = "To Upgrade",
	Options = {"utility", "efficiency", "quality"},
	CurrentOption = "utility",
	Flag = "TotemDropUpgrade", 
	Callback = function(Option)
		_G.SelectedUpgrade = Option
	end,
})


local Slider = Tab:CreateSlider({
	Name = "Level",
	Range = {1, 53},
	Increment = 1,
	Suffix = "Level",
	CurrentValue = 25,
	Flag = "TotemLevel",
	Callback = function(Value)
		_G.TotemLevel = Value
	end,
})

Toggle = Tab:CreateToggle({
	Name = "Auto Upgrade",
	CurrentValue = false,
	Flag = "MobAutoFarmButton", 
	Callback = function(Value)
		if Value == true then
			_G.AutoUpgradeTotem = true 
		else
			_G.AutoUpgradeTotem = false
		end
	end,
})

Toggle = Tab:CreateToggle({
	Name = "Auto Collect Items!",
	CurrentValue = false,
	Flag = "AJIGnb", 
	Callback = function(Value)
		if Value == true then
			_G.AutoCollectTotemItems = true 
		else
			_G.AutoCollectTotemItems = false
		end
	end,
})


local CropUpgrabers = {"totemWheat", "totemPineapple", "totemCarrot", "totemDragonfruit", "totemGrape", "totemMelon", "totemOnion", "totemPotato", "totemPumpkin", "totemRadish", "totemSpinach", "totemTomato"}
local StoneUpgrabers = {}

function GetName(Real)
	local Selected

	for i,v in pairs(CropUpgrabers) do
		if v == Real then
			Selected = "totem_crop"
		end
	end

	DebugCheck(0,"Selected: "..Selected)

	return Selected
end

]]

	local VoidFarmSelection = Tabs.Main:AddSection("Void Farm")

	local voidParasiteFarm = VoidFarmSelection:AddToggle("voidParasiteFarm", {Title = "voidParasiteFarm", Default = false })

	voidParasiteFarm:OnChanged(function()

		local Value = Options.voidParasiteFarm.Value

		if Value == true then
			_G.voidParasiteFarm = true
		else
			_G.voidParasiteFarm = false
		end
	end)

	local voidParasiteUseSichle = VoidFarmSelection:AddToggle("voidParasiteUseSichle", {Title = "voidParasiteUseSichle", Default = false })

	voidParasiteUseSichle:OnChanged(function()

		local Value = Options.voidParasiteUseSichle.Value

		if Value == true then
			_G.VoidParasiteSichle = true
		else
			_G.VoidParasiteSichle = false
		end
	end)

	local voidParasiteBypassCooldown = VoidFarmSelection:AddToggle("voidParasiteBypassCooldown", {Title = "Bypass Cooldown", Default = false })

	voidParasiteBypassCooldown:OnChanged(function()

		local Value = Options.voidParasiteBypassCooldown.Value

		if Value == true then
			_G.VoidParasiteBypass = true
		else
			_G.VoidParasiteBypass = false
		end
	end)

	local SpiritFarmSelection = Tabs.Main:AddSection("Spirit Farm")

	local SpiritFarm = SpiritFarmSelection:AddToggle("SpiritFarm", {Title = "SpiritFarm", Default = false })

	SpiritFarm:OnChanged(function()

		local Value = Options.SpiritFarm.Value

		if Value == true then
			_G.SpiritAutoFarmBool = true
		else
			_G.SpiritAutoFarmBool = false
		end
	end)

	local TeleportsSelection = Tabs.Teleports:AddSection("Teleports")

	TeleportsSelection:AddButton({
		Title = "Teleport Home",
		Description = "",
		Callback = function()
			OwnISland()
		end
	})

	TeleportsSelection:AddButton({
		Title = "Teleport Hub",
		Description = "",
		Callback = function()

			local Portal = nil

			local Island = GetIsland()
			local Blocks = Island:FindFirstChild("Blocks")

			if not Portal or Portal.Parent ~= GetIsland():FindFirstChild("Blocks") then
				print("No Portal set... Getting!")
				local Island = GetIsland()
				if Island and Island:FindFirstChild("Blocks") then
					for i,v in pairs(Island:FindFirstChild("Blocks"):GetChildren()) do 
						if v:FindFirstChild("PortalActive") and v:FindFirstChild("portal-to-spawn") then
							Portal = v
						end
					end 
				end 
			end

			if Blocks then
				-- local Portal = Blocks:FindFirstChild("portalToSpawn")
				if Portal then
					local CollisionBoxes = Portal:FindFirstChild("CollisionBoxes")
					if CollisionBoxes then
						Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CollisionBoxes:FindFirstChild("Part").CFrame
					end
				else
					local Island = GetIsland()
					if Island and Island:FindFirstChild("Blocks") then
						local Portal = game:FindFirstChild("portalToSpawn")
						if Portal then
							local CollisionBoxes = Portal:FindFirstChild("CollisionBoxes")
							if CollisionBoxes then
								Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CollisionBoxes:FindFirstChild("Part").CFrame
							end
						end
					end 
				end

			end
		end
	})

	TeleportsSelection:AddButton({
		Title = "Teleport Slime",
		Description = "",
		Callback = function()
			Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(151.095261, 37.1357651, -734.216797, 0.659632802, 0.00193329761, -0.751585543, 0.000203342643, 0.999996185, 0.00275074691, 0.751588047, -0.0019673123, 0.659629822)
		end
	})
	TeleportsSelection:AddButton({
		Title = "Teleport Buf",
		Description = "",
		Callback = function()
			Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(885.378052, 180.972031, 23.2142296, -0.869998932, 0, -0.493053645, 0, 1, 0, 0.493053645, 0, -0.869998932)
		end
	})

	TeleportsSelection:AddButton({
		Title = "Teleport witch",
		Description = "",
		Callback = function()
			Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1709.62317, 448.131409, -204.412949, 0.789979517, -0, -0.613133252, 0, 1, -0, 0.613133252, 0, 0.789979517)
		end
	})
	TeleportsSelection:AddButton({
		Title = "Teleport Desert",
		Description = "",
		Callback = function()
			Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1475.44434, 342.177856, -875.548889, -0.0172599554, 0, 0.999851167, 0, 1, 0, -0.999851167, 0, -0.0172599554)
		end
	})

	TeleportsSelection:AddButton({
		Title = "Teleport Hub Mine",
		Description = "",
		Callback = function()
			Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(686.588013, 200.419006, -229.044998, 0.792934179, 0, 0.609307289, 0, 1, 0, -0.609307289, 0, 0.792934179)
			task.wait(3)
			TeleportV4(Vector3.new(251.06788635253906, 25.95274543762207, -635.4160766601562))
		end
	})

	TeleportsSelection:AddButton({
		Title = "Teleport Pirat island",
		Description = "",
		Callback = function()
			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.TravelPirateIsland:FireServer(false)
		end
	})

	TeleportsSelection:AddButton({
		Title = "Teleport Spiret island",
		Description = "",
		Callback = function()
			Game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(654.445801, 184.972031, -134.859695, 0.165726423, -0, -0.986171782, 0, 1, -0, 0.986171782, 0, 0.165726423)
		end
	})

	local BlockPrinterSelection = Tabs.BlockPrinter:AddSection("Block Printer")

	local StartBlock = nil
	local EndBlock = nil

	local BlockPrinterBlocks = BlockPrinterSelection:AddParagraph({
		Title = "- Blocks:",
		Content = "/"
	})
	local BlockPrinterTime = BlockPrinterSelection:AddParagraph({
		Title = "- Time:",
		Content = "/"
	})

	local BlockPrinterDestroyTime


	--local BlocksToPlaceParagraph = BP3Tab:CreateParagraph({Title = "Blocks: ", Content = "/"})
	--local BlocksTimeParagraph = BP3Tab:CreateParagraph({Title = "Time: ", Content = "/"})

	local DestroyBlocksTimeParagraph

	local selectionBox
	local selectionLasso
	local handles

	local MainPart 


	game:GetService("RunService").RenderStepped:Connect(function()
		if selectionBox then
			selectionBox.Color3 = _G.ResizeToolOutlineColor or Color3.fromRGB(65, 105, 225) -- dodger blue
		end
		if handles then
			handles.Color3 = _G.ResizeToolMoveButtonColor or Color3.fromRGB(65, 105, 225) -- dodger blue
		end
		if MainPart then
			MainPart.Transparency = _G.ResizeToolFillTransparency
			if _G.ResizeToolFillColor then
				MainPart.Color = _G.ResizeToolFillColor
			end
		end
	end)

	local previousDistance

	function GetBlockCount()
		local positions = {}

		local function checkPositions(start, finish)
			local minX = math.min(start.x, finish.x)
			local maxX = math.max(start.x, finish.x)
			local minY = math.min(start.y, finish.y)
			local maxY = math.max(start.y, finish.y)
			local minZ = math.min(start.z, finish.z)
			local maxZ = math.max(start.z, finish.z)
			return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
		end


		local start_BLOCK = _G.StartBlock or StartBlock
		local start = start_BLOCK.Position
		local finish_Block = _G.EndBlock or EndBlock
		local _finish = finish_Block.Position

		start, finish = checkPositions(start, _finish)



		for x = start.x, finish.x, 3 do
			for y = start.y, finish.y, 3 do
				for z = start.z, finish.z, 3 do
					positions[#positions + 1] = Vector3.new(x, y, z)
				end
			end
		end

		local BlockPlaceCount = 0
		for i,v in ipairs(positions) do
			BlockPlaceCount = BlockPlaceCount + 1
		end

		BlockPrinterBlocks:SetDesc(BlockPlaceCount)

		--BlocksToPlaceParagraph:Set({Title = "Blocks: ", Content = BlockPlaceCount/10})

		if BlockPrinterDestroyTime then
			BlockPrinterDestroyTime:SetDesc(BlockPlaceCount.." Secs")
		end	

		if _G.FastBlockPrinter == true then
			local TIME = BlockPlaceCount/30
			BlockPrinterTime:SetDesc(TIME.." sec")
		else
			local TIME = BlockPlaceCount/10
			BlockPrinterTime:SetDesc(TIME.." sec")
		end

		return BlockPlaceCount
	end


	function addBoxes(part)



		local position = part.Position
		local size = part.Size

		local oldPartR = game.Workspace:FindFirstChild("Part_R")
		if oldPartR then
			oldPartR:Destroy()
		end


		local part2 = Instance.new("Part")
		part2.Name = "Part_R"
		part2.Parent = game.Workspace
		part2.Size = Vector3.new(3, 3, 3)
		part2.Anchored = true
		part2.Transparency = 1
		part2.CanCollide = false
		part2.Position = Vector3.new(position.x + size.x/2 - part2.Size.x/2, position.y + size.y/2 - part2.Size.y/2, position.z + size.z/2 - part2.Size.z/2)
		part2.Color = Color3.new(1, 0, 0)
		part2.CastShadow = false
		part2.Material = Enum.Material.Neon


		local oldPartL = game.Workspace:FindFirstChild("Part_L")
		if oldPartL then
			oldPartL:Destroy()
		end


		local part3 = Instance.new("Part")
		part3.Name = "Part_L"
		part3.Parent = game.Workspace
		part3.Size = Vector3.new(3, 3, 3)
		part3.Anchored = true
		part3.Transparency = 1
		part3.CanCollide = false
		part3.Position = Vector3.new(position.x - size.x/2 + part3.Size.x/2, position.y - size.y/2 + part3.Size.y/2, position.z - size.z/2 + part3.Size.z/2)
		part3.Color = Color3.new(0, 0.6, 1)
		part3.CastShadow = false
		part3.Material = Enum.Material.Neon


		_G.StartBlock = game:GetService("Workspace")["Part_L"]
		_G.EndBlock = game:GetService("Workspace")["Part_R"]
		GetBlockCount()



	end

	function onHandlesDown(normal)
		DebugCheck(0,"handlesDown")
		previousDistance = 0
	end
	function onHandlesDrag(normal, distance)

		for i,v in pairs(game:GetService("Players"):GetChildren()) do
			if v.Character then
				for i,Part in pairs(v.Character:GetDescendants()) do
					if Part:IsA("MeshPart") or Part:IsA("Part") then
						if Part:FindFirstChild("OLD_CanTouch") then
							Part.CanTouch = false
						else
							local OLDSTATE = Instance.new("BoolValue", Part)
							OLDSTATE.Name = "OLD_CanTouch"
							OLDSTATE.Value = Part.CanTouch
							Part.CanTouch = false
						end
					end
				end
			end
		end

		local OldSIZE = nil
		local OldPOS = nil

		if handles.Adornee then
			local delta = distance - previousDistance
			if math.abs(delta) >= 3 then
				local sizeDelta = math.floor(delta / 3 + 0.5) * 3
				OldSIZE = handles.Adornee.Size
				OldPOS = handles.Adornee.Position
				if handles.Adornee:Resize(normal, sizeDelta) then
					print("Versuche zu Resizen")
					print("normal",normal)
					print("sizeDelta",sizeDelta)
					addBoxes(handles.Adornee)
					if handles.Adornee.Size.X < 3 or handles.Adornee.Size.Y < 3 or handles.Adornee.Size.Z < 3 then
						print("Kleiner als 0")
						handles.Adornee.Size = OldSIZE
						handles.Adornee.Position = OldPOS
					end
					previousDistance = distance
				else
					print(tostring(handles.Adornee.Size))
					print("Resize ging nicht!")
					print("normal",normal)
					print("sizeDelta",sizeDelta)
				end
			end
		end

		task.wait(1)

		for i,v in pairs(game:GetService("Players"):GetChildren()) do
			if v.Character then
				for i,Part in pairs(v.Character:GetDescendants()) do
					if Part:IsA("MeshPart") or Part:IsA("Part") then
						if Part:FindFirstChild("OLD_CanTouch") then
							local OLDSTATE = Part:FindFirstChild("OLD_CanTouch") 
							Part.CanTouch = OLDSTATE.Value
						end
					end
				end
			end
		end
	end

	function onButton1Down(mouse)
		if _G.ResizeTool == true and _G.ChangePartOfResizeTool == true then
			_G.ChangePartOfResizeTool = false
			DebugCheck(0,"3DButtonDown")
			if mouse.Target == nil or mouse.Target.Locked then
				print("No Target or Locked!")
				selectionBox.Adornee = nil
				handles.Adornee = nil
			else
				local OLD = mouse.Target

				if OLD:FindFirstChild("Health") and OLD.Size.X == 3 then
					local NP 

					if game:GetService("Workspace"):FindFirstChild("NewPart") then
						NP = game:GetService("Workspace"):FindFirstChild("NewPart") 
					else
						NP = Instance.new("Part",workspace)
					end


					NP.Name = "NewPart"
					NP.Transparency = 1
					NP.Anchored = true
					NP.Size = OLD.Size
					NP.Position = OLD.Position
					NP.CanCollide = false
					NP.CastShadow = false
					NP.Material = Enum.Material.Neon
					selectionBox.Adornee = NP
					handles.Adornee = NP
					handles.Faces = NP.ResizeableFaces
					MainPart = NP
				else
					print(tostring(OLD.Size))
				end 

			end
		end
	end




	function onEquippedLocal(mouse)
		mouse.Button1Down:connect(function() onButton1Down(mouse) end)

		local character = game.Players.LocalPlayer.Character
		local player = game.Players:GetPlayerFromCharacter(character)

		selectionBox = Instance.new("SelectionBox")
		selectionBox.Color = BrickColor.Blue()
		selectionBox.Adornee = nil
		selectionBox.Parent = game:GetService("CoreGui")

		handles = Instance.new("Handles")
		handles.Color3 = _G.ResizeToolMoveButtonColor or Color3.fromRGB(65, 105, 225) -- dodger blue
		handles.Adornee = nil
		handles.MouseDrag:connect(onHandlesDrag)
		handles.MouseButton1Down:connect(onHandlesDown)
		handles.Parent = game:GetService("CoreGui")
	end

	function onUnequippedLocal()
		if selectionBox then
			selectionBox:Remove()
		end
		if handles then
			handles:Remove()
		end
	end

	local UseResizeTool = BlockPrinterSelection:AddToggle("UseResizeTool", {Title = "Use Resize Tool", Default = false })

	UseResizeTool:OnChanged(function()
		local Value = Options.UseResizeTool.Value
		if Value == true then
			_G.ResizeTool = true 
			onEquippedLocal(game.Players.LocalPlayer:GetMouse())
			_G.ChangePartOfResizeTool = true
		else
			onUnequippedLocal(game.Players.LocalPlayer:GetMouse())
			if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
				game:GetService("Workspace").NewPart:Destroy()
			end
			if 	game:GetService("Workspace"):FindFirstChild("Part_R") then
				game:GetService("Workspace").Part_R:Destroy()
			end
			if 	game:GetService("Workspace"):FindFirstChild("Part_L") then
				game:GetService("Workspace").Part_L:Destroy()
			end
			_G.ResizeTool = false 

			_G.ChangePartOfResizeTool = true
		end
	end)

	BlockPrinterSelection:AddButton({
		Title = "Change Position",
		Description = "",
		Callback = function()
			_G.ChangePartOfResizeTool = true
		end
	})

	function DebugCheck(N,Text)
		if _G.DebugMode == true then
			rconsolename("Debug")
			if N == nil then
				N = 0
			end 
			if N == 0 then
				rconsoleprint("\n"..Text)
			end
		end
	end

	function DebugCheck(N,Text)
		if _G.DebugMode == true then
			rconsolename("Debug")
			if N == nil then
				N = 0
			end 
			if N == 0 then
				rconsoleprint("\n"..Text)
			end
		end
	end

	function MoveToolGenPrimarypart(model)
		if model and model:IsA("Model") then
			if model:FindFirstChild("PrimaryPart") == nil then			
				local cf = model:GetBoundingBox()
				local prim = Instance.new("Part", model)
				prim.Anchored = true
				prim.Name = "PrimaryPart"
				-- prim.Size = model:GetModelSize()
				prim.Transparency = 0.5
				prim.CFrame = cf
				prim.CanCollide = false
				model.PrimaryPart = prim
				for i, v in next, model:GetDescendants() do
					if v.Parent == game.Players.LocalPlayer.Character or v.Parent.Name == game.Players.LocalPlayer.Name then

					else
						if (not v:IsA("BasePart")) and v ~= game.Players.LocalPlayer.Character and v.Parent ~= game.Players.LocalPlayer.Character then end -- continue
						local w = Instance.new("WeldConstraint", prim)
						w.Part0 = prim
						w.Part1 = v
					end
				end
				model.PrimaryPart = prim
			else
				-- gibts halt schon tf
			end
		end
	end

	function findCenter(Table)
		local parts = Table:GetChildren()
		local numVisibleParts = 0
		local totalPosition = Vector3.new(0, 0, 0)
		local MittigsterBlock = nil


		for _, part in ipairs(parts) do
			if part:IsA("Part") or part:IsA("MeshPart") then
				print(part.Name)
				totalPosition = totalPosition + part.Position
				MittigsterBlock = part
				numVisibleParts = numVisibleParts + 1
			else
				print(part.Name.." ist ein "..part.ClassName)
			end
		end


		if numVisibleParts > 0 then
			local centerPos = totalPosition / numVisibleParts
			return MittigsterBlock
		else
			return nil 
		end
	end

	function LoadRotateTool()
		local runService = game:GetService("RunService")
		local tweenService = game:GetService("TweenService")

		local player = game.Players.LocalPlayer
		local character = player.Character or player.CharacterAdded:Wait()

		local playerGui = player.PlayerGui 
		local mouse = player:GetMouse()

		local ancestor = Instance.new("Folder", game:GetService("CoreGui"))


		local rotateHandles = Instance.new("Folder", game:GetService("CoreGui"))


		local X_AXIS = Instance.new("ArcHandles")
		X_AXIS.Color3 = Color3.new(250,0,0)
		X_AXIS.Transparency = 0
		X_AXIS.Visible = true
		X_AXIS.Parent = rotateHandles

		local Y_AXIS = Instance.new("ArcHandles")
		Y_AXIS.Color3 = Color3.new(0, 255, 0)
		Y_AXIS.Transparency = 0
		Y_AXIS.Visible = true
		Y_AXIS.Parent = rotateHandles


		local Z_AXIS = Instance.new("ArcHandles")
		Z_AXIS.Color3 = Color3.new(0, 0, 255)
		Z_AXIS.Transparency = 0
		Z_AXIS.Visible = true
		Z_AXIS.Parent = rotateHandles

		local hoverBox = Instance.new("SelectionBox")
		hoverBox.Color3 = Color3.fromRGB(25, 153, 255)
		hoverBox.LineThickness = 0.04
		hoverBox.SurfaceColor3 = Color3.fromRGB(25, 153, 255)
		hoverBox.Parent = game:GetService("StarterGui")

		local selectedBox = Instance.new("SelectionBox")
		selectedBox.Color3 = Color3.fromRGB(25, 153, 255)
		selectedBox.LineThickness = 0.02
		selectedBox.SurfaceColor3 = Color3.fromRGB(25, 153, 255)
		selectedBox.Parent = game:GetService("StarterGui")

		local selectionBoxes = hoverBox and selectedBox

		local lastCFrame = CFrame.identity

		local originalCollisions = nil
		local originalTransparency = nil

		if not _G.currentlySelected then
			_G.currentlySelected = nil
		end

		function animateHoverBox()
			local hoverTween = tweenService:Create(
				hoverBox,
				TweenInfo.new(1, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut, -1, true, 0),
				{Color3 = Color3.fromRGB(25, 153, 255)})

			hoverTween:Play()
			return hoverTween
		end

		function rotateSnap(distance, step)
			return math.floor(distance / step) * step
		end

		local RotateCOoldown = false
		function onRotate(axis, angle)
			local step = (90 / 180) * math.pi
			local newAngle = CFrame.fromAxisAngle(Vector3.FromAxis(axis), rotateSnap(angle, step))

			local gewuenschteDrehung = CFrame.Angles(math.rad(90), 0, 0)

			if RotateCOoldown == false then
				RotateCOoldown = true
				CloneFolder:SetPrimaryPartCFrame(CloneFolder:GetPrimaryPartCFrame() * newAngle)
				task.wait(0.3)
				RotateCOoldown = false
			end

				--[[

				for i, v in pairs(CloneFolder:GetChildren()) do
					if v:IsA("Part") or v:IsA("MeshPart") then
						-- Speichere die ursprüngliche CFrame des Teils
						local originalCFrame = v.CFrame
						
						-- Berechne die neue CFrame unter Berücksichtigung der Rotation
						local rotatedCFrame = originalCFrame * newAngle
						
						-- Setze die CFrame des Teils auf die berechnete gedrehte CFrame
						v.CFrame = rotatedCFrame
					end
				end

				]]

			-- _G.currentlySelected.CFrame = lastCFrame * newAngle
		end


		function onSelect()
			local target = mouse.Target

			if target and target:IsA("Model") or target:IsA("BasePart") and target.Locked == false and target.ClassName ~= "Terrain" then
				originalCollisions = target.CanCollide
				originalTransparency = target.Transparency

				for i, handle in next, rotateHandles:GetChildren() do
					if handle:IsA("ArcHandles") then
						handle.Adornee = target
					end
				end

				_G.currentlySelected = target
				selectedBox.Adornee = target
			elseif not target then
				for i, handle in next, rotateHandles:GetChildren() do
					if handle:IsA("ArcHandles") then
						handle.Adornee = nil
					end
				end

				_G.currentlySelected = nil
				selectedBox.Adornee = nil
			end
		end

		function onEquipped()
			selectionBoxes.Name = "RotateSelectionBoxes"
			selectionBoxes.Parent = playerGui

			rotateHandles.Parent = playerGui

			if _G.currentlySelected then
				originalCollisions = _G.currentlySelected.CanCollide
				originalTransparency = _G.currentlySelected.Transparency

				for i, handle in next, rotateHandles:GetChildren() do
					if handle:IsA("ArcHandles") then
						handle.Adornee = _G.currentlySelected
					end
				end

				selectedBox.Adornee = _G.currentlySelected
			end
		end

		function onEquipped2()

			function findCenter(Table)
				local parts = Table:GetChildren()
				local numVisibleParts = 0
				local totalPosition = Vector3.new(0, 0, 0)
				local MittigsterBlock = nil


				for _, part in ipairs(parts) do
					if part:IsA("Part") or part:IsA("MeshPart") then
						print(part.Name)
						totalPosition = totalPosition + part.Position
						MittigsterBlock = part
						numVisibleParts = numVisibleParts + 1
					else
						print(part.Name.." ist ein "..part.ClassName)
					end
				end


				if numVisibleParts > 0 then
					local centerPos = totalPosition / numVisibleParts
					return MittigsterBlock
				else
					return nil 
				end
			end

			local MiddlePart = findCenter(CloneFolder)

			if not MiddlePart then return nil end;

			selectionBoxes.Name = "RotateSelectionBoxes"
			selectionBoxes.Parent = playerGui

			rotateHandles.Parent = playerGui

			_G.currentlySelected = MiddlePart

			if _G.currentlySelected then
				originalCollisions = _G.currentlySelected.CanCollide
				originalTransparency = _G.currentlySelected.Transparency

				for i, handle in next, rotateHandles:GetChildren() do
					if handle:IsA("ArcHandles") then
						handle.Adornee = _G.currentlySelected
					end
				end

				selectedBox.Adornee = _G.currentlySelected
			end
		end

		function onUnequipped()
			if _G.currentlySelected then
				_G.currentlySelected.CanCollide = originalCollisions
				_G.currentlySelected.Transparency = originalTransparency
			end

			rotateHandles.Parent = ancestor
			selectionBoxes.Parent = ancestor
		end

		function onHover()
			local target = mouse.Target

			if ancestor.Parent == character and target and target.Locked == false then
				hoverBox.Adornee = target
			else
				hoverBox.Adornee = nil
			end
		end

		function onHold()
			lastCFrame = _G.currentlySelected.CFrame

			_G.currentlySelected.Transparency = _G.currentlySelected.Transparency + 0.3
			_G.currentlySelected.CanCollide = false
		end

		function onRelease()
			if _G.currentlySelected then
				local object = _G.currentlySelected
				object.Size = _G.currentlySelected.Size
				object.Position = _G.currentlySelected.Position
				object.Orientation = _G.currentlySelected.Orientation

				_G.currentlySelected.Transparency = originalTransparency
				_G.currentlySelected.CanCollide = originalCollisions
			end
		end

		for i, handle in next, rotateHandles:GetChildren() do
			if handle:IsA("ArcHandles") then
				handle.MouseDrag:connect(onRotate)
				handle.MouseButton1Down:connect(onHold)
				handle.MouseButton1Up:connect(onRelease)
			end
		end

		animateHoverBox()

		mouse.Move:connect(onHover)

		game:GetService("Players").LocalPlayer:GetMouse().Button1Down:Connect(function()
			if _G.UseRotateTool == true then
				onSelect()
			end	
		end)

		_G.UseRotateTool = false

		Toggle = BP3Tab:CreateToggle({
			Name = "Use Rotation Tool [BETA!]",
			CurrentValue = false,
			Flag = "Use Rotation Tool", 
			Callback = function(Value)
				--_G.UseRotateTool = Value
				if Value == true then
					onEquipped2()
					--onEquipped()
				else
					pcall(onUnequipped)
				end
			end,
		})

	end

	--LoadRotateTool()

	function LoadMovingTool()
		local moveHandle = Instance.new("Handles")
		moveHandle.Parent = game:GetService("CoreGui")
		moveHandle.Color3 = Color3.fromRGB(218, 133, 65)
		moveHandle.Style = Enum.HandlesStyle.Movement

		local selectedBox = Instance.new("SelectionBox")
		selectedBox.Color3 = Color3.fromRGB(25, 153, 255)
		selectedBox.LineThickness = 0.02
		selectedBox.SurfaceColor3 = Color3.fromRGB(25, 153, 255)
		selectedBox.Parent = game:GetService("CoreGui")


		local hoverBox = Instance.new("SelectionBox")
		hoverBox.Color3 = Color3.fromRGB(25, 153, 255)
		hoverBox.LineThickness = 0.04
		hoverBox.SurfaceColor3 = Color3.fromRGB(25, 153, 255)
		hoverBox.Parent = game:GetService("CoreGui")

		local player = game.Players.LocalPlayer
		local mouse = player:GetMouse()

		local selected = nil
		local orignalTransparency = nil

		local lastCframe = CFrame.identity

		function activated()

			print("activated")

			function findCenter(Table)
				local parts = Table:GetChildren()
				local numVisibleParts = 0
				local totalPosition = Vector3.new(0, 0, 0)
				local MittigsterBlock = nil


				for _, part in ipairs(parts) do
					if part:IsA("Part") or part:IsA("MeshPart") then
						print(part.Name)
						totalPosition = totalPosition + part.Position
						MittigsterBlock = part
						numVisibleParts = numVisibleParts + 1
					else
						print(part.Name.." ist ein "..part.ClassName)
					end
				end


				if numVisibleParts > 0 then
					local centerPos = totalPosition / numVisibleParts
					return MittigsterBlock
				else
					return nil 
				end
			end

			local MiddlePart = findCenter(CloneFolder)

			if not MiddlePart then return nil end;

			if CloneFolder and CloneFolder.PrimaryPart then

			else
				CloneFolder.PrimaryPart = MiddlePart
			end	


			local target = CloneFolder:FindFirstChild("PrimaryPart") or CloneFolder.PrimaryPart

			if target and target.Locked == false then
				print("Jup")
				selected = target
				orignalTransparency = selected.Transparency

				moveHandle.Parent = game.Players.LocalPlayer.PlayerGui
				moveHandle.Adornee = selected

				hoverBox.Parent = selected
				hoverBox.Adornee = selected

				selectedBox.Parent = selected
				selectedBox.Adornee = selected
			else
				selected = nil
				orignalTransparency = nil

				hoverBox.Parent = game:GetService("CoreGui")
				hoverBox.Adornee = selected

				moveHandle.Parent = game:GetService("CoreGui")
				moveHandle.Adornee = selected

				selectedBox.Parent = game:GetService("CoreGui")
				selectedBox.Adornee = selected
			end
		end

		function hoverSelection()
			local target = mouse.Target

			if target and target.Locked == false then
				hoverBox.Parent = target
				hoverBox.Adornee = target
			else
				hoverBox.Parent = game:GetService("CoreGui")
				hoverBox.Adornee = target
			end
		end

		function moveSnap(distance, step)
			return math.round(distance / step) * step
		end

		function onMove(face, distance)
			local step = moveSnap(distance, selected.ResizeIncrement)
			local move = Vector3.FromNormalId(face) * step

			local stepSize = 3
			local roundedDistance = math.floor(distance / stepSize + 0.5) * stepSize
			local resizedStep = moveSnap(roundedDistance, selected.ResizeIncrement)
			local resizedMove = Vector3.FromNormalId(face) * resizedStep

			print("move:",move)

			print("roundedDistance:",roundedDistance)

			print("resizedStep:",resizedStep)

			print("resizedMove:",resizedMove)

			-- selected.CFrame = lastCframe * CFrame.new(resizedMove)

			CloneFolder:SetPrimaryPartCFrame(lastCframe * CFrame.new(resizedMove))

		end

		function onHold()
			lastCframe = selected.CFrame
			selected.Transparency = selected.Transparency + 0.3
			selected.CanCollide = false
		end

		function onRelease()	
			selected.Transparency = orignalTransparency
			--selected.CanCollide = true
		end

		function unequipped()
			moveHandle.Parent = game:GetService("CoreGui")
			moveHandle.Adornee = nil -- selected

			hoverBox.Parent = game:GetService("CoreGui")
			hoverBox.Adornee = nil -- selected

			selectedBox.Parent = game:GetService("CoreGui")
			selectedBox.Adornee = nil -- selected
		end

		moveHandle.MouseDrag:connect(onMove)
		moveHandle.MouseButton1Down:connect(onHold)
		moveHandle.MouseButton1Up:connect(onRelease)
		--mouse.Move:connect(hoverSelection)

		--[[

		game:GetService("UserInputService").InputBegan:Connect(function(input, processed)
			if not processed and input.UserInputType == Enum.UserInputType.MouseButton1 then
				activated()
			end
		end)

		]]


		local UseMovingTool = BlockPrinterSelection:AddToggle("UseMovingTool", {Title = "Use Moving Tool", Default = false })

		UseMovingTool:OnChanged(function()
			local Value = Options.UseMovingTool.Value
			if Value == true then
				activated()
			else
				pcall(unequipped)
			end
		end)


		-- unequipped()
	end

	LoadMovingTool()

	local BlockPrinterSpeed = BlockPrinterSelection:AddSlider("BlockPrinterSpeed", {
		Title = "Block Printer Speed",
		Description = "",
		Default = 5,
		Min = 1,
		Max = 20,
		Rounding = 0,
		Callback = function(Value)
			print("Slider was changed:", Value)
		end
	})

	BlockPrinterSpeed:OnChanged(function(Value)
		_G.PlayerBlockPrinterSpeed = Value
	end)



	function ADDUPPDATEEEEEEE()
		local positions = {}
		local function checkPositions(start, finish)
			local minX = math.min(start.x, finish.x)
			local maxX = math.max(start.x, finish.x)
			local minY = math.min(start.y, finish.y)
			local maxY = math.max(start.y, finish.y)
			local minZ = math.min(start.z, finish.z)
			local maxZ = math.max(start.z, finish.z)
			return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
		end

		local start = _G.StartBlock.Position
		local finish = _G.EndBlock.Position
		start, finish = checkPositions(start, finish)

		for x = start.x, finish.x, 3 do
			for y = start.y, finish.y, 3 do
				for z = start.z, finish.z, 3 do
					positions[#positions + 1] = Vector3.new(x, y, z)
				end
			end
		end
	end

	function ADDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD(positions,XX)

		local ADDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDANTILAG = false

		local MAXPLACEDIS = XX or 50

		for i,v in ipairs(positions) do
			if v ~= nil then
				-- TeleportV4(v + Vector3.new(0,10,0))
			end
		end


		local FFFFPOS = {}

		for i,v in pairs(positions) do
			if v then
				FFFFPOS[i] = v
			end
		end

		game:GetService("RunService").RenderStepped:connect(function()
			if ADDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDANTILAG == false then
				ADDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDANTILAG = true
				for i,v in ipairs(FFFFPOS) do
					if v then

						local ToLace
						local Tool = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool")
						if Tool then
							ToLace = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name
						end



						local Tool = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool")
						if Tool then
							if Tool:FindFirstChild("seeds") then
								function removeSeeds(itemName)
									local index = string.find(itemName, "Seeds")
									if index ~= nil then
										return string.sub(itemName, 1, index - 1)
									else
										return itemName
									end
								end
								ToLace = removeSeeds(ToLace)
								_G.CropModus = true
							else
								_G.CropModus = false
							end
						end
						local PlaceHASHName = RemoteData:FindFirstChild("BlockPlaceHashData").Value
						local PlaceHASH = _G.BlockPlaceHash
						if (v - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude < MAXPLACEDIS  then
							local args = {
								["upperBlock"] = false,
								["cframe"] = CFrame.new(v),
								["blockType"] = ToLace,
								[PlaceHASHName] = PlaceHASH
							}


							game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(args)
							FFFFPOS[i] = nil
						end
					end
				end
				task.wait()
				ADDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDANTILAG = false
			end 
		end)
	end



	function PlaceBlocksNew()

		local BlockCount = 1

		local StartPosition = game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart")

		local function PlaceBlock(position, ToLace, PlaceHASHName, PlaceHASH)
			local args = {
				[PlaceHASHName] = PlaceHASH,
				["cframe"] = CFrame.new(position),
				["blockType"] = ToLace,
				["upperBlock"] = false
			}
			if _G.BlockPrinterTP == true then
				TeleportV4(position + Vector3.new(0,10,0))
			end
			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(args)
		end

		if not game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool") then Message("WARNING!","Please Hold the Block you want to Place!", "Okay!", 3) return nil end 

		if _G.StartBlock == nil and _G.EndBlock == nil then Message("WARNING!","StartBlock and Endblock are not Set!", "Okay!", 3) return nil end

		if _G.StartBlock == nil then Message("WARNING!","StartBlock is not Set!", "Okay!", 3) return nil end

		if _G.EndBlock == nil then Message("WARNING!","EndBlock is not Set!", "Okay!", 3) return nil end

		local ToLace

		local Tool = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool")
		if Tool then
			if Tool:FindFirstChild("seeds") then
				function removeSeeds(itemName)
					local index = string.find(itemName, "Seeds")
					if index ~= nil then
						return string.sub(itemName, 1, index - 1)
					else
						return itemName
					end
				end
				ToLace = removeSeeds(Tool.Name)
				_G.CropModus = true
				DebugCheck(0,"Crop Mode: true")
			else
				ToLace = Tool.Name
				_G.CropModus = false
			end
		end


		for _, child in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
			if child:IsA("BasePart") and child.CanCollide == true then
				child.CanCollide = false
			end
		end

		if _G.BlockPrinterTP == true then
			sFLY(true)
		end

		local positions = {}

		local function checkPositions(start, finish)
			local minX = math.min(start.x, finish.x)
			local maxX = math.max(start.x, finish.x)
			local minY = math.min(start.y, finish.y)
			local maxY = math.max(start.y, finish.y)
			local minZ = math.min(start.z, finish.z)
			local maxZ = math.max(start.z, finish.z)
			return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
		end

		local start = _G.StartBlock.Position
		local finish = _G.EndBlock.Position
		start, finish = checkPositions(start, finish)

		for x = start.x, finish.x, 3 do
			for y = start.y, finish.y, 3 do
				for z = start.z, finish.z, 3 do
					positions[#positions + 1] = Vector3.new(x, y, z)
				end
			end
		end



		local BlockPlaceCount = 0
		for i,v in ipairs(positions) do
			BlockPlaceCount = BlockPlaceCount + 1
		end

		task.spawn(function()
			if positions[1] then
				TeleportV4(positions[1] + Vector3.new(0,15,0))
				PlaceBlock(positions[1], ToLace, PlaceHASHName, PlaceHASH)
			end
		end)

		DebugCheck(0,"To Place: "..BlockPlaceCount)

		if _G.BlockPrinterTP == true then
			game.Players.LocalPlayer.Character:MoveTo(game.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0,10,0))
		end

		task.wait(2)

		for i = 1,_G.PlayerBlockPrinterSpeed do
			for i,v in pairs(positions) do
				task.wait()
				task.spawn(function()
					if v then
						local dis = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v).Magnitude
						if dis > 30 then
							if _G.BlockPrinterTP == true then
								TeleportV4(v + Vector3.new(0,10,0))
								repeat wait(0.1) TeleportV4(v + Vector3.new(0,10,0)) until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - v).Magnitude < 30
								if v then
									PlaceBlock(v, ToLace, PlaceHASHName, PlaceHASH)
									positions[i] = nil
								end
							else
								if v then
									PlaceBlock(v, ToLace, PlaceHASHName, PlaceHASH)
									positions[i] = nil
								end
							end
						else
							if v then
								PlaceBlock(v, ToLace, PlaceHASHName, PlaceHASH)
								positions[i] = nil
							end
						end
					end
				end)
			end
		end

		print("positions debug: ",type(positions))

		if type(positions) == "table" then
			for i,v in pairs(positions) do
				warn(i,v)
			end
		else
			print("OTHER TYPE OF POSITIONS!",type(positions))
		end

		repeat wait() print("Es gibt noch positions!", positions) until positions == nil or #positions == 0

		DebugCheck(0,"FERTIG!!!!!")

		NOFLY()

		Message("Finished!","Block Printer Finished! (Teleporting back to Start Position...)", "Nice!", 3)

		task.wait(0.1)

		TeleportV4(StartPosition)

	end


	local function DestroyBlocksNew()

		local BlockCount = 1

		local saved = {}

		local function DestroyBlock(Block)
			DebugCheck(0,"DestroyBlock_FUJNC")
			if Block then
				local H1 = RemoteData:FindFirstChild("TreeHashData").Value
				local H2 = _G.TreeHash

				local ohTable1 = {
					[H1] = H2,
					["part"] = Block,
					["block"] = Block,
					["norm"] = v,
					["pos"] = 0
				}
				TeleportV4(Block.Position + Vector3.new(0,10,0))
				game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
				task.wait(1)
				if Block then
					table.insert(saved,Block)
				end
			end
		end

		if _G.StartBlock == nil and _G.EndBlock == nil then Message("WARNING!","StartBlock and Endblock are not Set!", "Okay!", 3) return nil end

		if _G.StartBlock == nil then Message("WARNING!","StartBlock is not Set!", "Okay!", 3) return nil end

		if _G.EndBlock == nil then Message("WARNING!","EndBlock is not Set!", "Okay!", 3) return nil end

		local ToLace


		for _, child in pairs(game.Players.LocalPlayer.Character:GetDescendants()) do
			if child:IsA("BasePart") and child.CanCollide == true then
				child.CanCollide = false
			end
		end

		if _G.BlockPrinterTP == true then
			sFLY(true)
		end


		task.wait(0.1)

		local positions = {}

		task.wait(1)

		-- AUG

		local function findNearestPart(A)
			local closestPart = nil
			local closestDistance = math.huge
			local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

			local Table = A

			for i, part in ipairs(Table) do
				local distance = (part.Position - playerPosition).magnitude
				if distance < closestDistance then
					closestPart = part
					closestDistance = distance
				end
			end

			DebugCheck(0,"findNearestPart")

			return closestPart
		end

		if 	game:GetService("Workspace"):FindFirstChild("NewPart") then

			local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
			local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)

			-- Funktion zum Finden des nächsten Teils


			for i = 1,_G.PlayerBlockPrinterSpeed do
				for i,SB in pairs(BLOCKS) do
					task.wait()
					task.spawn(function()
						if SB and SB.Parent and SB.Parent.Name == "Blocks" then
							DebugCheck(0,"SB:",SB.Name)
							local dis = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - SB.Position).Magnitude
							if dis > 30 then
								DebugCheck(0,"IDS")
								if _G.BlockPrinterTP == true then
									TeleportV4(SB.Position + Vector3.new(0,10,0))
									repeat wait(0.1) TeleportV4(SB.Position + Vector3.new(0,10,0)) until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - SB.Position).Magnitude < 30
									if v then
										DebugCheck(0,"VTRUE")
										DestroyBlock(SB)
										saved[i] = nil
									end
								else
									if v then
										DebugCheck(0,"VFALSE")
										DestroyBlock(SB)
										saved[i] = nil
									end
								end
							else
								DebugCheck(0,"NODIS")
								if SB then
									DebugCheck(0,"VELSEFALSE")
									DestroyBlock(SB)
									saved[i] = nil
								end
							end
						end
					end)
				end
			end
		end

		for i = 1,100 do
			if saved == {} then

			else
				local positions = {}

				local function checkPositions(start, finish)
					local minX = math.min(start.x, finish.x)
					local maxX = math.max(start.x, finish.x)
					local minY = math.min(start.y, finish.y)
					local maxY = math.max(start.y, finish.y)
					local minZ = math.min(start.z, finish.z)
					local maxZ = math.max(start.z, finish.z)
					return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
				end

				local start = _G.StartBlock.Position
				local finish = _G.EndBlock.Position
				start, finish = checkPositions(start, finish)

				for x = start.x, finish.x, 3 do
					for y = start.y, finish.y, 3 do
						for z = start.z, finish.z, 3 do
							positions[#positions + 1] = Vector3.new(x, y, z)
						end
					end
				end

				if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
					local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
					local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)
					for i,SB in pairs(BLOCKS) do
						task.spawn(function()
							if SB and SB.Parent and SB.Parent.Name == "Blocks" then

								local H1 = RemoteData:FindFirstChild("TreeHashData").Value
								local H2 = _G.TreeHash

								local ohTable1 = {
									[H1] = H2,
									["part"] = SB,
									["block"] = SB,
									["norm"] = v,
									["pos"] = 0
								}


								local RemotesToSend = _G.RemotesToSendToDestroy or 3

								for i = 1,1 do
									game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
								end



								task.wait()

							end
						end)

					end
				end

				for i = 1,_G.PlayerBlockPrinterSpeed do
					for i,SB in pairs(saved) do
						task.wait()
						task.spawn(function()
							if SB and SB.Parent and SB.Parent.Name == "Blocks" then
								DebugCheck(0,"SB:",SB.Name)
								local dis = (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - SB.Position).Magnitude
								if dis > 10 then
									DebugCheck(0,"IDS")
									if _G.BlockPrinterTP == true then
										TeleportV4(SB.Position + Vector3.new(0,10,0))
										repeat wait(0.1) TeleportV4(SB.Position + Vector3.new(0,10,0)) until (game.Players.LocalPlayer.Character.HumanoidRootPart.Position - SB.Position).Magnitude < 10
										if v then
											DebugCheck(0,"VTRUE")
											DestroyBlock(SB)
											saved[i] = nil
										end
									else
										if v then
											DebugCheck(0,"VFALSE")
											DestroyBlock(SB)
											saved[i] = nil
										end
									end
								else
									DebugCheck(0,"NODIS")
									if SB then
										DebugCheck(0,"VELSEFALSE")
										DestroyBlock(SB)
										saved[i] = nil
									end
								end
							end

						end)
					end
				end
			end
			local positions = {}

			local function checkPositions(start, finish)
				local minX = math.min(start.x, finish.x)
				local maxX = math.max(start.x, finish.x)
				local minY = math.min(start.y, finish.y)
				local maxY = math.max(start.y, finish.y)
				local minZ = math.min(start.z, finish.z)
				local maxZ = math.max(start.z, finish.z)
				return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
			end

			local start = _G.StartBlock.Position
			local finish = _G.EndBlock.Position
			start, finish = checkPositions(start, finish)

			for x = start.x, finish.x, 3 do
				for y = start.y, finish.y, 3 do
					for z = start.z, finish.z, 3 do
						positions[#positions + 1] = Vector3.new(x, y, z)
					end
				end
			end

			if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
				local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
				local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)
				for i,SB in pairs(BLOCKS) do
					task.spawn(function()
						if SB and SB.Parent and SB.Parent.Name == "Blocks" then

							local H1 = RemoteData:FindFirstChild("TreeHashData").Value
							local H2 = _G.TreeHash

							local ohTable1 = {
								[H1] = H2,
								["part"] = SB,
								["block"] = SB,
								["norm"] = v,
								["pos"] = 0
							}


							local RemotesToSend = _G.RemotesToSendToDestroy or 3

							for i = 1,1 do
								game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
							end

							task.wait()

						end
					end)

				end
			end

		end

		DebugCheck(0,"FERTIG!!!!!")

		NOFLY()

	end

	BlockPrinterSelection:AddButton({
		Title = "Print Blocks",
		Description = "",
		Callback = function()
			PlaceBlocksNew()
		end
	})

	_G.GetBlockMethod = "Place Block"

	local InputService = game:GetService("UserInputService")
	InputService.InputBegan:Connect(function(inputObject)
		if inputObject.UserInputType == Enum.UserInputType.MouseButton1 then

		--[[-
		local mouseHit = Vector3.new(game.Players.LocalPlayer:GetMouse().Hit
		if _G.GetBlockMethod == "MouseClick" then
			if _G.GetStartBlock == true then
				_G.StartBlock = mouseHit
				_G.GetStartBlock = false
			elseif _G.GetEndBlock == true then
				_G.EndBlock = mouseHit
				_G.GetEndBlock = false
			end
		--]]

			if _G.GetBlockMethod == "Place Block" then
				if _G.GetStartBlock == true then
					local Island = GetIsland()
					local Blocks  = Island:FindFirstChild("Blocks")

					local STARTADDED = Blocks.ChildAdded:connect(function(v)
						if _G.GetStartBlock == true then
							if v.Name == game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name then
								StartBlockParagraph:Set({Title = "StartBlock: ", Content = ":GreenCube: | "..v.Name})
								_G.StartBlock = v
								StartBlock = v
								_G.GetStartBlock = false
								if _G.StartBlock ~= nil and _G.EndBlock ~= nil then
									GetBlockCount()
								end
								STARTADDED:Disconnect()

							end
						end
					end)
				elseif _G.GetEndBlock == true then
					local Island = GetIsland()
					local Blocks  = Island:FindFirstChild("Blocks")

					local ENDADDED = Blocks.ChildAdded:connect(function(v)
						if _G.GetEndBlock == true then
							if v.Name == game.Players.LocalPlayer.Character:FindFirstChildOfClass("Tool").Name then
								EndBlockParagraph:Set({Title = "EndBlock: ", Content = ":GreenCube: | "..v.Name})
								_G.EndBlock = v
								EndBlock = v
								_G.GetEndBlock = false
								if _G.StartBlock ~= nil and _G.EndBlock ~= nil then
									GetBlockCount()
								end
								ENDADDED:Disconnect()
							end
						end
					end)
				end
			end
		end
	end)


	function COPYPASTEGUI()
		-- Block Destroy -- 
		local BlockDestroySelection = Tabs.BlockPrinter:AddSection("Block Destroyer")

		BlockPrinterDestroyTime = BlockPrinterSelection:AddParagraph({
			Title = "- Time:",
			Content = "/"
		})


	--[[

	
	local Button = BP3Tab:CreateButton({
		Name = "Destroy Blocks",
		Callback = function()
			local positions = {}

			local function checkPositions(start, finish)
				local minX = math.min(start.x, finish.x)
				local maxX = math.max(start.x, finish.x)
				local minY = math.min(start.y, finish.y)
				local maxY = math.max(start.y, finish.y)
				local minZ = math.min(start.z, finish.z)
				local maxZ = math.max(start.z, finish.z)
				return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
			end

			local start = _G.StartBlock.Position
			local finish = _G.EndBlock.Position
			start, finish = checkPositions(start, finish)

			for x = start.x, finish.x, 3 do
				for y = start.y, finish.y, 3 do
					for z = start.z, finish.z, 3 do
						positions[#positions + 1] = Vector3.new(x, y, z)
					end
				end
			end

			if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
				local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
				local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)
				for i,SB in pairs(BLOCKS) do
					if SB and SB.Parent and SB.Parent.Name == "Blocks" then
						
					local H1 = RemoteData:FindFirstChild("TreeHashData").Value
					local H2 = _G.TreeHash

					local ohTable1 = {
						[H1] = H2,
						["part"] = SB,
						["block"] = SB,
						["norm"] = v,
						["pos"] = 0
					}


					local RemotesToSend = _G.RemotesToSendToDestroy or 3

					for i = 1,1 do
						game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
					end

					task.wait()

					end
				end
			end

		end,
	})

	]]

		BlockDestroySelection:AddButton({
			Title = "Instant Destroy Blocks (Greg´s Hammer)",
			Description = "",
			Callback = function()
				local positions = {}

				local function checkPositions(start, finish)
					local minX = math.min(start.x, finish.x)
					local maxX = math.max(start.x, finish.x)
					local minY = math.min(start.y, finish.y)
					local maxY = math.max(start.y, finish.y)
					local minZ = math.min(start.z, finish.z)
					local maxZ = math.max(start.z, finish.z)
					return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
				end

				local start = _G.StartBlock.Position
				local finish = _G.EndBlock.Position
				start, finish = checkPositions(start, finish)

				for x = start.x, finish.x, 3 do
					for y = start.y, finish.y, 3 do
						for z = start.z, finish.z, 3 do
							positions[#positions + 1] = Vector3.new(x, y, z)
						end
					end
				end

				if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
					local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
					local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)
					for i,SB in pairs(BLOCKS) do
						task.spawn(function()
							if SB and SB.Parent and SB.Parent.Name == "Blocks" then

								local H1 = RemoteData:FindFirstChild("TreeHashData").Value
								local H2 = _G.TreeHash

								local ohTable1 = {
									[H1] = H2,
									["part"] = SB,
									["block"] = SB,
									["norm"] = v,
									["pos"] = 0
								}


								local RemotesToSend = _G.RemotesToSendToDestroy or 3

								for i = 1,1 do
									game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.CLIENT_BLOCK_HIT_REQUEST:InvokeServer(ohTable1)
								end

								task.wait()

							end
						end)

					end
				end

			end
		})


		BlockDestroySelection:AddButton({
			Title = "Destroy Blocks [BETA!]",
			Description = "",
			Callback = function()
				DestroyBlocksNew()
			end
		})


		local LASTSAVEDSDATA

		local CopyPasteSelection = Tabs.BlockPrinter:AddSection("Copy / paste!")

		CopyPasteSelection:AddButton({
			Title = "Clone Blocks",
			Description = "",
			Callback = function()
				for i,v in ipairs(CloneFolder:GetChildren()) do
					v:Destroy()
					DebugCheck(0,v.Name.." Got Deleted!")
				end


				local positions = {}

				local function checkPositions(start, finish)
					local minX = math.min(start.x, finish.x)
					local maxX = math.max(start.x, finish.x)
					local minY = math.min(start.y, finish.y)
					local maxY = math.max(start.y, finish.y)
					local minZ = math.min(start.z, finish.z)
					local maxZ = math.max(start.z, finish.z)
					return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
				end

				local start = _G.StartBlock.Position
				local finish = _G.EndBlock.Position
				start, finish = checkPositions(start, finish)

				for x = start.x, finish.x, 3 do
					for y = start.y, finish.y, 3 do
						for z = start.z, finish.z, 3 do
							positions[#positions + 1] = Vector3.new(x, y, z)
						end
					end
				end

				if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
					local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
					local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)
					for i,SB in pairs(BLOCKS) do
						if SB.Parent.Name == "Blocks" then
							local NEWSB = SB:Clone()
							NEWSB.Parent = CloneFolder
							NEWSB.Position = SB.Position + Vector3.new(0,3,0)

							NEWSB.Transparency = 0.5
						end
					end
				end

			end
		})

		CopyPasteSelection:AddButton({
			Title = "Paste Blocks",
			Description = "",
			Callback = function()
				a = pcall(function()
					unequipped()
				end)

				local WAITGAY_XE = 0

				local CCPL = 0

				local positions = {}

				for i,v in pairs(CloneFolder:GetChildren()) do
					if v then
						positions[i] = v
						DebugCheck(0,"Added:",v.Name)
					end
				end

				local PLOW = false

				--[[

					local BBBBBB = GetIsland():FindFirstChild("Blocks").ChildAdded:Connect(function(v)
					if PLOW == true and v and v.Name == "grass" then
						local DIS = (v.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
						if DIS < 50 then
							PLOW = false
							local args = {
								[1] = {
									["block"] = v
								}
							}


							game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_PLOW_BLOCK_REQUEST:InvokeServer(unpack(args))	

						end
					else
						DebugCheck(0,"WARN GAY!!!")
					end
				end)

				]]

				for i,pos in pairs(positions) do
					task.spawn(function()

						local Block = positions[i]
						local pos = Block.CFrame
						--if pos and Block then
						if Block.Name == "soil" then
							Block.Name = "grass"
							PLOW = true
						end

						local distance = (Block.Position - game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").Position).Magnitude

						print("distance:",distance)

						if distance > 30 then

							TeleportV4(Block.Position)

							repeat wait() until (Block.Position - game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart").Position).Magnitude < 30

							local args = {
								[1] = {
									["upperBlock"] = false,
									["cframe"] = pos, -- CFrame.new(Vector3.new(pos.x, pos.y, pos.z, 1, 0, 0, 0, 1, 0, 0, 0, 1))
									["blockType"] = Block.Name,
									[CropPlaceH1] = CropPlaceH2
								}
							}

							game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(unpack(args))	

						else
							local args = {
								[1] = {
									["upperBlock"] = false,
									["cframe"] = pos, -- CFrame.new(Vector3.new(pos.x, pos.y, pos.z, 1, 0, 0, 0, 1, 0, 0, 0, 1))
									["blockType"] = Block.Name,
									[CropPlaceH1] = CropPlaceH2
								}
							}

							game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(unpack(args))

						end


						--end
					end)
				end


				--[[

				for i, pos in ipairs(positions) do
					CCPL = CCPL + 1
					if positions[CCPL] then


						local Block = positions[CCPL]
						DebugCheck(0,Block.Name)
						local pos = Block.CFrame


						if pos and Block then

							if Block.Name == "soil" then
								Block.Name = "grass"
								PLOW = true
							end

							local args = {
								[1] = {
									["upperBlock"] = false,
									["cframe"] = pos, -- CFrame.new(Vector3.new(pos.x, pos.y, pos.z, 1, 0, 0, 0, 1, 0, 0, 0, 1))
									["blockType"] = Block.Name,
									[CropPlaceH1] = CropPlaceH2
								}
							}

							game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(unpack(args))

							if  positions[CCPL+1] then
								if positions[CCPL+1].Name == "soil" then
									positions[CCPL+1].Name = "grass"
									PLOW = true
								end

								local args = {
									[1] = {
										["upperBlock"] = false,
										["cframe"] = positions[CCPL+1].CFrame, -- CFrame.new(Vector3.new(pos.x, pos.y, pos.z, 1, 0, 0, 0, 1, 0, 0, 0, 1))
										["blockType"] = positions[CCPL+1].Name,
										[CropPlaceH1] = CropPlaceH2
									}
								}

								game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(unpack(args))
							end

							if  positions[CCPL+2] then
								if positions[CCPL+2].Name == "soil" then
									positions[CCPL+2].Name = "grass"
									PLOW = true
								end

								local args = {
									[1] = {
										["upperBlock"] = false,
										["cframe"] = positions[CCPL+2].CFrame, -- CFrame.new(Vector3.new(pos.x, pos.y, pos.z, 1, 0, 0, 0, 1, 0, 0, 0, 1))
										["blockType"] = positions[CCPL+2].Name,
										[CropPlaceH1] = CropPlaceH2
									}
								}

								game:GetService("ReplicatedStorage").rbxts_include.node_modules:FindFirstChild("@rbxts").net.out._NetManaged.CLIENT_BLOCK_PLACE_REQUEST:InvokeServer(unpack(args))
							end

						end


					end
				end

				]]

				task.wait(5)

				for i,v in pairs(CloneFolder:GetChildren()) do
					if v then
						v:Destroy()
					end
				end
			end
		})


		local FileName = ""

		local Files = GetSchematicaFiles()

		local inputString = Files[1]
		if inputString then
			local parts = {}
			for part in inputString:gmatch("[^\\]+") do
				table.insert(parts, part)
			end
			local outputString = parts[#parts]
			FileName = outputString
		end

		local Dropdown_Files = CopyPasteSelection:AddDropdown("Dropdown_Files", {
			Title = "Files",
			Values = Files,
			Multi = false,
			Default = 1,
		})

		Dropdown_Files:OnChanged(function(Value)
			if type(Value) == "string" then
				local inputString = Value
				local parts = {}
				for part in inputString:gmatch("[^\\]+") do
					table.insert(parts, part)
				end
				local outputString = parts[#parts]
				FileName = outputString
			end


		end)

		task.spawn(function()
			while wait(5) do
				Dropdown_Files:SetValues(GetSchematicaFiles())
			end
		end)

		local FileNameInput = CopyPasteSelection:AddInput("FileName", {
			Title = "File Name",
			Default = "Template",
			Placeholder = "Template.tmp",
			Numeric = false, -- Only allows numbers
			Finished = false, -- Only calls callback when you press enter
			Callback = function(Value)
				FileName = Value
			end
		})

		CopyPasteSelection:AddButton({
			Title = "Save Blocks to File!",
			Description = "",
			Callback = function()
				for i,v in ipairs(CloneFolder:GetChildren()) do
					v:Destroy()
					DebugCheck(0,v.Name.." Got Deleted!")
				end


				local positions = {}

				local function checkPositions(start, finish)
					local minX = math.min(start.x, finish.x)
					local maxX = math.max(start.x, finish.x)
					local minY = math.min(start.y, finish.y)
					local maxY = math.max(start.y, finish.y)
					local minZ = math.min(start.z, finish.z)
					local maxZ = math.max(start.z, finish.z)
					return Vector3.new(minX, minY, minZ), Vector3.new(maxX, maxY, maxZ)
				end

				local start = _G.StartBlock.Position
				local finish = _G.EndBlock.Position
				start, finish = checkPositions(start, finish)

				for x = start.x, finish.x, 3 do
					for y = start.y, finish.y, 3 do
						for z = start.z, finish.z, 3 do
							positions[#positions + 1] = Vector3.new(x, y, z)
						end
					end
				end

				-- HIER --

				local function isVisible(part)
					return part.Transparency == 0 and part.CanCollide == true and part.Size.X > 0 and part.Size.Y > 0 and part.Size.Z > 0
				end

				function findCenter(Table)
					local parts = Table
					local numVisibleParts = 0
					local totalPosition = Vector3.new(0, 0, 0)
					local MittigsterBlock = nil


					for _, part in ipairs(parts) do
						if part:IsA("Part") or part:IsA("MeshPart") then
							print(part.Name)
							totalPosition = totalPosition + part.Position
							MittigsterBlock = part
							numVisibleParts = numVisibleParts + 1
						else
							print(part.Name.." ist ein "..part.ClassName)
						end
					end


					if numVisibleParts > 0 then
						local centerPos = totalPosition / numVisibleParts
						return centerPos
					else
						return nil 
					end
				end

				local SaveData = {}

				if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
					local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
					local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)
					for i,v in pairs(BLOCKS) do
						if v.Parent.Name == "Blocks" then
							table.insert(SaveData, v)
						end
					end
				end

				local MittePosition = findCenter(SaveData)

				print("Der Part is ", tostring(MittePosition))

				local data = {
					Size = {tostring(game:GetService("Workspace"):FindFirstChild("NewPart").Size)},
					Blocks = {

					}
				}


				local function save(name, cframe)
					if not data.Blocks[name] then
						data.Blocks[name] = {}
					end
					table.insert(data.Blocks[name], {C = {cframe.components(cframe)}})
				end

				if 	game:GetService("Workspace"):FindFirstChild("NewPart") then
					local PART = game:GetService("Workspace"):FindFirstChild("NewPart")
					local BLOCKS = GetBlocks(PART.Position, PART.Size, PART)
					for i,v in pairs(BLOCKS) do
						if v.Parent.Name == "Blocks" then
							save(v.Name, v.CFrame)
						end
					end
				end

				DebugCheck(0,"PRINTING SOON!!!")

				task.wait()

				local json = game:GetService("HttpService")
				local dataString = json:JSONEncode(data)
				LASTSAVEDSDATA = dataString

				task.wait()

				if LASTSAVEDSDATA ~= nil then

					function GetMore()
						-- Beispiel-Tabelle von Strings
						local stringsTable = {"Nekohub on Top?",
							"BloodBath#9170 is Gay",
							"BloodBath#9170 is a Monkey",
							"BloodBath#9170 are you Mad? :clown:", 
							"Boss was here :)"
						}
						local randomIndex = math.random(#stringsTable)
						local randomString = stringsTable[randomIndex]
						return randomString or "Imagine you are Gay :skull:"

					end

					local WERBUNG = [[-- Generated With Islands.God (discord.gg/MbsxuDEzgT) Version: 0.4 Beta]].."\n".."--"..GetMore().." \n"

					CreateFile("/Schematica/"..FileName, WERBUNG.."\n"..LASTSAVEDSDATA, false)

					task.wait(0.5)

					Message("👍!", "Your File got successfully Saved! (Nekohub/Islands/Schematica)", "Nice!", 3)

				else
					DebugCheck(0,"LASTSAVEDSDATA ist nil")
				end

				DebugCheck(0,"done.")
			end
		})

		CopyPasteSelection:AddButton({
			Title = "Load File to Game!",
			Description = "",
			Callback = function()

				print("FileName:",FileName)

				local ALLBLOCKS = game:GetService("ReplicatedStorage").Blocks
				if IsFile("/Schematica/"..FileName) ~= nil then
					FILEDATA = ReadFile("/Schematica/"..FileName, LASTSAVEDSDATA)
					if FILEDATA then
						local text = FILEDATA
						local newText = text:gsub("%-%-.-\n", "\n")
						DebugCheck(0,newText)

						if newText then
							DebugCheck(0,"REMOVED!!!")
							FILEDATA = newText
						end

						DebugCheck(0,FILEDATA)

						task.wait()

						json = game:GetService("HttpService")
						jsonString = FILEDATA
						A = json:JSONDecode(jsonString)
						-- print the data
						if A.Blocks then
							for name, blocks in pairs(A.Blocks) do
								if ALLBLOCKS:FindFirstChild(name) then
									DebugCheck(0,name)
									if name == "dirt" then
										name = "soil" -- grass
									end
									for _, block in ipairs(blocks) do
										clone = ALLBLOCKS:FindFirstChild(name):FindFirstChild("Root"):Clone()
										if clone then
											clone.Transparency = 0.5
											clone.Name = name
											clone.Parent = CloneFolder
											clone.CFrame = CFrame.new(unpack(block.C))
											DebugCheck(0,"CE")
										else
											DebugCheck(0,"NO ROOT MONKEY!!")
										end
									end
								end
							end
						else
							print("Project Z file detected!")
							for name, blocks in pairs(A) do
								for _, block in ipairs(blocks) do
									local x, y, z = block[1], block[2], block[3]
									local position = Vector3.new(x, y, z)

									print("Block Name:", name)
									print("Block Position:", position)

									if ALLBLOCKS:FindFirstChild(name) then
										DebugCheck(0,name)
										if name == "dirt" then
											name = "soil" -- grass
										end
										clone = ALLBLOCKS:FindFirstChild(name):FindFirstChild("Root"):Clone()
										if clone then
											clone.Transparency = 0.5
											clone.Name = name
											clone.Parent = CloneFolder
											clone.CFrame = CFrame.new(position)
										end
									end
								end
							end
						end

						task.wait(0.3)

						activated()

						task.wait(0.2)

						Message("👍!", "Your File got Loaded successfully!", "Nice!", 3)

					end
				else
					DebugCheck(0,"LASTSAVEDSDATA ist nil")
				end
			end
		})



		local LastTarget = nil
		local NewTarget = false

		local BringParagraph

		local function onClick()
			if NewTarget then
				local mouse = game.Players.LocalPlayer:GetMouse()
				local Hit = mouse.Target 

				LastTarget = Hit 
				print("New Target",Hit)
				if Hit then
					BringParagraph:SetDesc("Target Found! "..Hit.Name)
					task.wait(1)
					BringParagraph:SetDesc("false")
				else
					BringParagraph:SetDesc("Error! Please try again!")
					task.wait(1)
					BringParagraph:SetDesc("false")
				end
				NewTarget = false
			end 
		end

		game:GetService("UserInputService").InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 then
				onClick() 
			end
		end)

		local TeleportBuildSelection = Tabs.BlockPrinter:AddSection("Teleport")

		BringParagraph = TeleportBuildSelection:AddParagraph({
			Title = "- Waiting for Click:",
			Content = "false"
		})

		TeleportBuildSelection:AddButton({
			Title = "Teleport to Player!",
			Description = "",
			Callback = function()
				pcall(unequipped)

				local function roundToMultipleOfThree(value)
					local roundedValue = math.floor(value / 3 + 0.5) * 3
					return roundedValue
				end

				local player = game.Players.LocalPlayer 
				local Position = player.Character.HumanoidRootPart.Position

				local roundedNumber_x = roundToMultipleOfThree(Position.X)
				local roundedNumber_y = roundToMultipleOfThree(Position.Y)
				local roundedNumber_z = roundToMultipleOfThree(Position.Z)

				local Final = Vector3.new(roundedNumber_x, roundedNumber_y, roundedNumber_z)


				if not Final then Message("Error", "NBF", "?", 1) return nil end

				local TargetBlockPos = Final

				if CloneFolder.PrimaryPart then
					CloneFolder:SetPrimaryPartCFrame(CFrame.new(TargetBlockPos))
				else
					MoveToolGenPrimarypart(CloneFolder)
					task.wait()
					CloneFolder:SetPrimaryPartCFrame(CFrame.new(TargetBlockPos))
				end

				task.wait()

				activated()

			end
		})

		function GetUnder3x3Block()
			local function IsApproximatelySize(part, targetSize, tolerance)
				local partSize = part.Size
				local sizeDifference = math.abs(partSize.X - targetSize.X) + math.abs(partSize.Y - targetSize.Y) + math.abs(partSize.Z - targetSize.Z)
				return sizeDifference <= tolerance
			end

			local function FindPartBelow(part)
				local raycastOrigin = part.Position
				local raycastDirection = Vector3.new(0, -3, 0) -- Richtung nach unten

				local raycastParams = RaycastParams.new()
				raycastParams.FilterType = Enum.RaycastFilterType.Blacklist

				-- Ignoriere Teile im gleichen Objekt und Teile mit dem Namen "Top"
				raycastParams.FilterDescendantsInstances = {part.Parent}
				raycastParams.IgnoreWater = true -- Optional: Ignoriere Wasser

				local hitResult = game.Workspace:Raycast(raycastOrigin, raycastDirection, raycastParams)

				if hitResult then
					local hitPart = hitResult.Instance
					if hitPart:IsA("BasePart") then
						if IsApproximatelySize(hitPart, Vector3.new(3, 3, 3), 0.1) then
							return hitPart -- Return the position of the found part
						else
							if IsApproximatelySize(hitPart.Parent, Vector3.new(3, 3, 3), 0.1) then
								return hitPart.Parent
							else
								return FindPartBelow(hitPart) -- Suche weiter darunter
							end
						end
					end
				end
			end

			local player = game.Players.LocalPlayer
			local character = player.Character

			if character then
				local humanoidRootPart = character:WaitForChild("HumanoidRootPart")
				local pos = FindPartBelow(humanoidRootPart)
				return pos
			else
				print("Charakter nicht gefunden.")
			end

		end

		TeleportBuildSelection:AddButton({
			Title = "Teleport to Nearest Block!",
			Description = "",
			Callback = function()
				unequipped()

				local C = CloneFolder:FindFirstChild("PrimaryPart") or CloneFolder.PrimaryPart

				local TargetBlock = GetUnder3x3Block()

				if not TargetBlock then Message("Error", "NBF", "?", 1) return nil end

				print("TargetBlock:",TargetBlock)

				local TargetBlockPos = TargetBlock.Position + Vector3.new(0,3,0)

				if CloneFolder.PrimaryPart then
					CloneFolder:SetPrimaryPartCFrame(CFrame.new(TargetBlockPos))
				else

					function findCenter(Table)
						local parts = Table:GetChildren()
						local numVisibleParts = 0
						local totalPosition = Vector3.new(0, 0, 0)
						local MittigsterBlock = nil


						for _, part in ipairs(parts) do
							if part:IsA("Part") or part:IsA("MeshPart") then
								print(part.Name)
								totalPosition = totalPosition + part.Position
								MittigsterBlock = part
								numVisibleParts = numVisibleParts + 1
							else
								print(part.Name.." ist ein "..part.ClassName)
							end
						end


						if numVisibleParts > 0 then
							local centerPos = totalPosition / numVisibleParts
							return MittigsterBlock
						else
							return nil 
						end
					end

					CloneFolder.PrimaryPart = findCenter(CloneFolder)
					task.wait()
					CloneFolder:SetPrimaryPartCFrame(CFrame.new(TargetBlockPos))
				end

				task.wait()

				activated()

			end
		})

		TeleportBuildSelection:AddButton({
			Title = "Teleport to Mouse!",
			Description = "",
			Callback = function()
				unequipped()





				LastTarget = nil
				NewTarget = false

				BringParagraph:SetDesc("true")

				function findCenter(Table)
					local parts = Table:GetChildren()
					local numVisibleParts = 0
					local totalPosition = Vector3.new(0, 0, 0)
					local MittigsterBlock = nil


					for _, part in ipairs(parts) do
						if part:IsA("Part") or part:IsA("MeshPart") then
							print(part.Name)
							totalPosition = totalPosition + part.Position
							MittigsterBlock = part
							numVisibleParts = numVisibleParts + 1
						else
							print(part.Name.." ist ein "..part.ClassName)
						end
					end


					if numVisibleParts > 0 then
						local centerPos = totalPosition / numVisibleParts
						return MittigsterBlock
					else
						return nil 
					end
				end

				local C = CloneFolder:FindFirstChild("PrimaryPart") or CloneFolder.PrimaryPart


				if CloneFolder.PrimaryPart then
					if LastTarget then
						if LastTarget.Name == "Top" then
							-- Preserve rotation and update X, Y, Z coordinates
							CloneFolder:SetPrimaryPartCFrame(CFrame.new(LastTarget.Parent.Position) * CFrame.fromMatrix(Vector3.new(), CloneFolder.PrimaryPart.CFrame.RightVector, CloneFolder.PrimaryPart.CFrame.UpVector))
						else
							-- Preserve rotation and update X, Y, Z coordinates
							CloneFolder:SetPrimaryPartCFrame(CFrame.new(LastTarget.Position) * CFrame.fromMatrix(Vector3.new(), CloneFolder.PrimaryPart.CFrame.RightVector, CloneFolder.PrimaryPart.CFrame.UpVector))
						end
					else
						NewTarget = true
						repeat wait() until LastTarget
						if LastTarget.Name == "Top" then
							-- Preserve rotation and update X, Y, Z coordinates
							CloneFolder:SetPrimaryPartCFrame(CFrame.new(LastTarget.Parent.Position) * CFrame.fromMatrix(Vector3.new(), CloneFolder.PrimaryPart.CFrame.RightVector, CloneFolder.PrimaryPart.CFrame.UpVector))
						else
							-- Preserve rotation and update X, Y, Z coordinates
							CloneFolder:SetPrimaryPartCFrame(CFrame.new(LastTarget.Position) * CFrame.fromMatrix(Vector3.new(), CloneFolder.PrimaryPart.CFrame.RightVector, CloneFolder.PrimaryPart.CFrame.UpVector))
						end
					end
				else
					DebugCheck(0, "NO PrimaryPart")
					MoveToolGenPrimarypart(CloneFolder)
					task.wait()
					if LastTarget then
						-- Preserve rotation and update X, Y, Z coordinates
						CloneFolder:SetPrimaryPartCFrame(CFrame.new(LastTarget.Position) * CFrame.fromMatrix(Vector3.new(), CloneFolder.PrimaryPart.CFrame.RightVector, CloneFolder.PrimaryPart.CFrame.UpVector))
					else
						NewTarget = true
						repeat wait() until LastTarget
						-- Preserve rotation and update X, Y, Z coordinates
						CloneFolder:SetPrimaryPartCFrame(CFrame.new(LastTarget.Position) * CFrame.fromMatrix(Vector3.new(), CloneFolder.PrimaryPart.CFrame.RightVector, CloneFolder.PrimaryPart.CFrame.UpVector))
					end
				end

				task.wait()

				activated()

			end
		})


		CopyPasteSelection:AddButton({
			Title = "unLoad file to game",
			Description = "",
			Callback = function()
				pcall(unequipped)

				task.wait()

				if CloneFolder then
					for i,v in pairs(CloneFolder:GetChildren()) do
						v:Destroy()
					end
				end
			end
		})

		_G.BuildCollision = true
		local BuildCollision = CopyPasteSelection:AddToggle("BuildCollision", {Title = "Build Collision", Default = true })

		BuildCollision:OnChanged(function(Value)
			_G.BuildCollision = Value
		end)

		task.spawn(function()
			while wait() do
				for i,v in pairs(CloneFolder:GetChildren()) do
					if v:IsA("Part") or v:IsA("MeshPart") then
						v.CanCollide = _G.BuildCollision
					end
				end	
			end
		end)

	end

	COPYPASTEGUI()



	-- Move --

	local OtherStuffSelection = Tabs.BlockPrinter:AddSection("Other Stuff")

	OtherStuffSelection:AddButton({
		Title = "Rotate 90 X",
		Description = "",
		Callback = function()

			function findCenter(Table)
				local parts = Table:GetChildren()
				local numVisibleParts = 0
				local totalPosition = Vector3.new(0, 0, 0)
				local MittigsterBlock = nil


				for _, part in ipairs(parts) do
					if part:IsA("Part") or part:IsA("MeshPart") then
						print(part.Name)
						totalPosition = totalPosition + part.Position
						MittigsterBlock = part
						numVisibleParts = numVisibleParts + 1
					else
						print(part.Name.." ist ein "..part.ClassName)
					end
				end


				if numVisibleParts > 0 then
					local centerPos = totalPosition / numVisibleParts
					return MittigsterBlock
				else
					return nil 
				end
			end

			if CloneFolder.PrimaryPart == nil then
				if CloneFolder:FindFirstChild("PrimaryPart") then
					CloneFolder:FindFirstChild("PrimaryPart"):Destroy()
				end

				local C = findCenter(CloneFolder)
				CloneFolder.PrimaryPart = C
				task.wait(0.5)
			end

			local gewuenschteDrehung = CFrame.Angles(math.rad(90), 0, 0)

			CloneFolder:SetPrimaryPartCFrame(CloneFolder:GetPrimaryPartCFrame() * gewuenschteDrehung)
		end
	})

	OtherStuffSelection:AddButton({
		Title = "Rotate 90 Y",
		Description = "",
		Callback = function()

			function findCenter(Table)
				local parts = Table:GetChildren()
				local numVisibleParts = 0
				local totalPosition = Vector3.new(0, 0, 0)
				local MittigsterBlock = nil


				for _, part in ipairs(parts) do
					if part:IsA("Part") or part:IsA("MeshPart") then
						print(part.Name)
						totalPosition = totalPosition + part.Position
						MittigsterBlock = part
						numVisibleParts = numVisibleParts + 1
					else
						print(part.Name.." ist ein "..part.ClassName)
					end
				end


				if numVisibleParts > 0 then
					local centerPos = totalPosition / numVisibleParts
					return MittigsterBlock
				else
					return nil 
				end
			end

			if CloneFolder.PrimaryPart == nil then
				if CloneFolder:FindFirstChild("PrimaryPart") then
					CloneFolder:FindFirstChild("PrimaryPart"):Destroy()
				end

				local C = findCenter(CloneFolder)
				CloneFolder.PrimaryPart = C
				task.wait(0.5)
			end

			local gewuenschteDrehung = CFrame.Angles(0, math.rad(90), 0)

			CloneFolder:SetPrimaryPartCFrame(CloneFolder:GetPrimaryPartCFrame() * gewuenschteDrehung)
		end
	})

	OtherStuffSelection:AddButton({
		Title = "Rotate 90 Z",
		Description = "",
		Callback = function()

			function findCenter(Table)
				local parts = Table:GetChildren()
				local numVisibleParts = 0
				local totalPosition = Vector3.new(0, 0, 0)
				local MittigsterBlock = nil


				for _, part in ipairs(parts) do
					if part:IsA("Part") or part:IsA("MeshPart") then
						print(part.Name)
						totalPosition = totalPosition + part.Position
						MittigsterBlock = part
						numVisibleParts = numVisibleParts + 1
					else
						print(part.Name.." ist ein "..part.ClassName)
					end
				end


				if numVisibleParts > 0 then
					local centerPos = totalPosition / numVisibleParts
					return MittigsterBlock
				else
					return nil 
				end
			end

			if CloneFolder.PrimaryPart == nil then
				if CloneFolder:FindFirstChild("PrimaryPart") then
					CloneFolder:FindFirstChild("PrimaryPart"):Destroy()
				end

				local C = findCenter(CloneFolder)
				CloneFolder.PrimaryPart = C
				task.wait(0.5)
			end

			local gewuenschteDrehung = CFrame.Angles(0, 0, math.rad(90))

			CloneFolder:SetPrimaryPartCFrame(CloneFolder:GetPrimaryPartCFrame() * gewuenschteDrehung)
		end
	})





	-- Player --
	local PlayerSelection = Tabs.Player:AddSection("Player")


--[[

local Button = Tab:CreateButton({
	Name = "God Mode",
	Callback = function()
		local Player=game.Players.LocalPlayer

		local Character=Player.Character

		function Bypass(S)

			local OLD = S
			if not OLD then return "Gay" end
			local NEW = OLD:Clone()
			OLD:Destroy()
			NEW.Parent = Character
		end

		Bypass(Character:FindFirstChild("LastDamagedTick"))

		game:GetService("Players").LocalPlayer.PlayerGui.Hotbar:FindFirstChild("1"):FindFirstChild("1"):FindFirstChild("1"):FindFirstChild("4").Text = "inf / inf"

	end,
})

]]

	PlayerSelection:AddButton({
		Title = "Cooldown bypass",
		Description = "",
		Callback = function()
			local Cooldown; Cooldown = hookfunction(wait, function(v)
				v = 0;
				return Cooldown(v);
			end);
		end
	})


	local PlayerFly = PlayerSelection:AddToggle("PlayerFly", {Title = "Fly", Default = false })

	PlayerFly:OnChanged(function(Value)
		if Value == true then
			sFLY(true)
		else
			NOFLY()
		end
	end)

	local AutoCompleteActionGame = PlayerSelection:AddToggle("Auto Complete Action Game", {Title = "Auto Complete Gam (SOON!)e", Default = false })

	AutoCompleteActionGame:OnChanged(function(Value)
		_G.AutoCompleteActionGame = Value
	end)

	local WaitUntilTheOldShitIsCompleted_MovingBarCompleteNiggaShit = false

	function checkPosition(frame, mid)
		local a1 = frame.AbsolutePosition.X
		local b1 = mid.AbsolutePosition.X

		local a2 = a1 + frame.AbsoluteSize.X
		local b2 = b1 + mid.AbsoluteSize.X


		if (b1 <= a1 and b2 <= a1) or (a2 <= b1 and a2 <= b2) then
			return false
		else
			task.wait(0.1)
			return true
		end
	end

	game:GetService("RunService").RenderStepped:Connect(function()

		if WaitUntilTheOldShitIsCompleted_MovingBarCompleteNiggaShit == true then return nil end

		function CompleteMovingBar()
			local re
			repeat
				re = checkPosition(game:GetService("Players").LocalPlayer.PlayerGui.ActionBarScreenGui.ActionBar.RoactTree:WaitForChild("3"):WaitForChild("Minigame"):WaitForChild("Marker"), game:GetService("Players").LocalPlayer.PlayerGui.ActionBarScreenGui.ActionBar.RoactTree:WaitForChild("3"):WaitForChild("Minigame"):WaitForChild("Marker")			)
				print(re)
				task.wait()
			until re == true
			game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
			game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)
			task.wait(0.5)
			WaitUntilTheOldShitIsCompleted_MovingBarCompleteNiggaShit = false
		end
	
		if _G.AutoCompleteActionGame == true then
			if game:GetService("Players").LocalPlayer.PlayerGui.ActionBarScreenGui.ActionBar:FindFirstChild("RoactTree") then
				if game:GetService("Players").LocalPlayer.PlayerGui.ActionBarScreenGui.ActionBar.RoactTree:WaitForChild("3"):WaitForChild("Minigame"):WaitForChild("Marker") then
					WaitUntilTheOldShitIsCompleted_MovingBarCompleteNiggaShit = true
					CompleteMovingBar()
				end
			end
		end
	
	end)

	local FlySpeedSlider = PlayerSelection:AddSlider("FlySpeedSlider", {
		Title = "Fly Speed",
		Description = "",
		Default = 1,
		Min = 0,
		Max = 10,
		Rounding = 1,
		Callback = function(Value)
			iyflyspeed = Value
		end
	})

	local JumpPowerSlider = PlayerSelection:AddSlider("JumpPowerSlider", {
		Title = "Jump Power",
		Description = "",
		Default = 50,
		Min = 0,
		Max = 500,
		Rounding = 0,
		Callback = function(Value)
			_G.JumpPower = Value
		end
	})


	local SpeedSlider = PlayerSelection:AddSlider("SpeedSlider", {
		Title = "Walk Speed",
		Description = "",
		Default = 30,
		Min = 0,
		Max = 40,
		Rounding = 0,
		Callback = function(Value)
			_G.WalkSpeed = Value
		end
	})




	_G.BuySellType = 0
	_G.MaxPriceVendingSniper = 0

	local SelectedItemParagraph = Tabs.VendingSniper:AddParagraph({
		Title = "Selected Item:",
		Content = "-"
	})

	local StatusVendingParagraph = Tabs.VendingSniper:AddParagraph({
		Title = "Status:",
		Content = "-"
	})



	function FindWithVendingSniper(Target, MaxPrice)
		local ISTHERE = false
		DebugCheck(0,"FindWithVendingSniper")
		local Island = game:GetService("Workspace").Islands:FindFirstChildWhichIsA("Model")
		local Blocks = Island:FindFirstChild("Blocks")
		DebugCheck(0,"BLOCK1")
		for i,v in pairs(Blocks:GetChildren()) do
			if v.Name == "vendingMachine" or v.Name == "vendingMachine1" or v.Name == "vendingMachine2" then
				if v:FindFirstChild("SellingContents") then
					if v:FindFirstChild("SellingContents"):FindFirstChild(Target) then
						if v:FindFirstChild("Mode") then
							DebugCheck(0,"MODE")
							if v:FindFirstChild("Mode").Value == _G.BuySellType then
								if v:FindFirstChild("TransactionPrice") then
									if v:FindFirstChild("TransactionPrice").Value > MaxPrice then
										DebugCheck(0,"GOOD PRICE!! ")
										DebugCheck(0,v:FindFirstChild("SellingContents"):FindFirstChild(Target).Name)
										StatusVendingParagraph:SetDesc("The Item: "..Target.." Was Found!")
										MiniTp(v.Position + Vector3.new(0,10,0))
										ISTHERE = true
										task.wait(2)
										StatusVendingParagraph:SetDesc("-")
									end
								end
							end
						end
					end
				end
			end
		end
		if ISTHERE == false then
			DebugCheck(0,"No "..Target.." Found!")
			StatusVendingParagraph:SetDesc( "The Item: "..Target.." Was not Found or Cost too much!")
			task.wait(2)
			StatusVendingParagraph:SetDesc("-")
		else
			StatusVendingParagraph:SetDesc("The Item: "..Target.." Was Found!")
			task.wait(2)
			StatusVendingParagraph:SetDesc("-")
		end
	end

	local Input = Tabs.VendingSniper:AddInput("Input", {
		Title = "MaxPrice",
		Default = "0",
		Placeholder = "0",
		Numeric = true, -- Only allows numbers
		Finished = false, -- Only calls callback when you press enter
		Callback = function(Value)
			_G.MaxPriceVendingSniper = tonumber(Value)
		end
	})

	local BuyOrSellOption = Tabs.VendingSniper:AddDropdown("BuyOrSellOption", {
		Title = "Select Option",
		Values = {"Buy", "Sell"},
		Multi = false,
		Default = 1,
	})

	BuyOrSellOption:OnChanged(function(Value)
		if Option == "Buy" then
			_G.BuySellType = 0
		elseif Option == "Sell" then
			_G.BuySellType = 1
		end
	end)

	Tabs.VendingSniper:AddButton({
		Title = "Select Holding tool",
		Description = "",
		Callback = function()
			local TOOL = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool")
			if TOOL then
				_G.FindingItemVendingSniper = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool").Name
				SelectedItemParagraph:SetDesc(TOOL.Name)
			end
		end
	})

	Tabs.VendingSniper:AddButton({
		Title = "Find Item",
		Description = "",
		Callback = function()
			local MaxPrice = _G.MaxPriceVendingSniper
			local ITEMTOFIND = _G.FindingItemVendingSniper
			FindWithVendingSniper(ITEMTOFIND, MaxPrice)
		end
	})



	if DidKey == false then


--[[
_G.MobFarmAnimationBypass = true
local Section = Tab:CreateSection("Mob")
local BRINGMOBSDNJUGA = Tab:CreateToggle({
	Name = "Bypass Mob Farm Animation",
	CurrentValue = true,
	Flag = "Bypass Mob Farm Animation Toggle", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
	Callback = function(Value)
		if Value == true then
			game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, true, game, 1)
			_G.MobFarmAnimationBypass = true
			task.wait(0.5)
			game:GetService("VirtualInputManager"):SendMouseButtonEvent(0, 0, 0, false, game, 1)
		else
			_G.MobFarmAnimationBypass = false
		end
	end,
})

]]
		local MobTeleportSelection = Tabs.BypassFun:AddSection("Mob Teleport [BETA!]")


		_G.MobBringY = 0
		_G.MobBringSelectedMob = "All"

		local MobYPosition = MobTeleportSelection:AddSlider("MobYPosition", {
			Title = "Y Position",
			Description = "",
			Default = 1,
			Min = -20,
			Max = 30,
			Rounding = 0,
			Callback = function(Value)
				_G.MobBringY = Value
			end
		})

		local SelectMobToBypass = MobTeleportSelection:AddDropdown("SelectMobToBypass", {
			Title = "Select Mob",
			Values = {"All","slime", "buffalkor", "wizardLizard","Skorpions","magmaBlob","magmaGolem","skeletonPirate","voidPup","voidDog"},
			Multi = false,
			Default = 2,
		})

		SelectMobToBypass:OnChanged(function(Option)
			if type(Option) == "table" then
				_G.MobBringSelectedMob = Option[1]
			else
				_G.MobBringSelectedMob = Option
			end
		end)

		local BringBypassedMobs = MobTeleportSelection:AddToggle("BringBypassedMobs", {Title = "Bring Mobs", Default = false })

		BringBypassedMobs:OnChanged(function(Value)
			_G.BringMobsEnabled = Value
		end)

		task.spawn(function()
			while  wait(0.1) do
				if _G.BringMobsEnabled == true then
					local speaker = game.Players.LocalPlayer
					local YPOS = _G.MobBringY or 20
					local TargetPos = speaker.Character.Head.Position + Vector3.new(0, YPOS, 0)
					local UnflyAfterSec = 2000000
					local Forces = {}

					for _, part in pairs(game:GetService("Workspace").WildernessIsland.Entities:GetDescendants()) do
						if speaker.Character:FindFirstChild('Head')
							and part:IsA("BasePart") or part:IsA("UnionOperation" or part:IsA("Model"))
							and not part.Anchored and not part:IsDescendantOf(speaker.Character)
							and part.Name ~= "Torso" and part.Name ~= "Head"
							and part.Name ~= "Right Arm" and part.Name ~= "Left Arm"
							and part.Name ~= "Right Leg" and part.Name ~= "Left Leg"
							and part.Name ~= "HumanoidRootPart" then

							if _G.MobBringSelectedMob == "All" then
								for i, c in pairs(part:GetChildren()) do
									if c:IsA("BodyPosition") or c:IsA("BodyGyro") then
										c:Destroy()
									end
								end

								local ForceInstance = Instance.new("BodyPosition")
								ForceInstance.Parent = part
								ForceInstance.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
								table.insert(Forces, ForceInstance)

								coroutine.wrap(function()
									wait(UnflyAfterSec)
									ForceInstance:Destroy()
								end)()
							else
								if part.Name == _G.MobBringSelectedMob or part.Parent.Name == _G.MobBringSelectedMob then
									for i, c in pairs(part:GetChildren()) do
										if c:IsA("BodyPosition") or c:IsA("BodyGyro") then
											c:Destroy()
										end
									end

									local ForceInstance = Instance.new("BodyPosition")
									ForceInstance.Parent = part
									ForceInstance.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
									table.insert(Forces, ForceInstance)

									coroutine.wrap(function()
										wait(UnflyAfterSec)
										ForceInstance:Destroy()
									end)()
								end
							end
						end
					end

					for i, c in pairs(Forces) do
						c.Position = TargetPos
					end



				else
					for _, part in pairs(game:GetService("Workspace").WildernessIsland.Entities:GetDescendants()) do
						for i, c in pairs(part:GetChildren()) do
							if c:IsA("BodyPosition") or c:IsA("BodyGyro") then
								c:Destroy()
							end
						end
					end
				end
			end
		end)

		local BypassedToolsSelection = Tabs.BypassFun:AddSection("Tools")

		function GetTool(TOOLNAME, BackonChanged, BreakToolname)
			for i,v in pairs(game:GetService("ReplicatedStorage").Tools:GetChildren()) do
				if v.Name == TOOLNAME and v:IsA("Tool") then
					local Clone = v:Clone()
					Clone.Parent = game.Players.LocalPlayer.Backpack


					-- v:FindFirstChild("DisplayName").Value = ""
					if BackonChanged == true then

						function Invisble(Tool, V)
							local TOCHAN 
							if V == true then
								TOCHAN = 1
							else
								TOCHAN = 0
							end

							if Tool:FindFirstChild("Handle") then
								if Tool:FindFirstChild("Handle"):IsA("Part") or Tool:FindFirstChild("Handle"):IsA("MeshPart") then
									Tool:FindFirstChild("Handle").Transparency = TOCHAN
									for i,v in pairs(Tool:FindFirstChild("Handle"):GetChildren()) do
										if v then
											if v:IsA("Part") or v:IsA("MeshPart") then
												v.Transparency = TOCHAN
											end
										end
									end
								end
							end

						end 

						local Back = false
						if game.Players.LocalPlayer.Character:FindFirstChild(BreakToolname) then
							Back = true
						end
						game.Players.LocalPlayer.Character.ChildAdded:Connect(function(Added)
							if Added.Name == BreakToolname then
								Back = true
							end
						end)



						game.Players.LocalPlayer.Character.ChildRemoved:Connect(function(Added)
							if Added.Name == BreakToolname then
								if game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname) then
									if game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname):FindFirstChild("axe") then
										game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname):FindFirstChild("axe").Enabled = true
										Invisble(game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname), false)
									end
								end
								-- Back = false
							end
						end)

						Clone.Changed:Connect(function(Changed)
							if Changed == "Parent" then
								if Back == true then
									if game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname) then
										if game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname) then
											if game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname):FindFirstChild("axe") then
												game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname):FindFirstChild("axe").Enabled = false
												Invisble(game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname), true)
											end
										end
										game.Players.LocalPlayer.Backpack:FindFirstChild(BreakToolname).Parent = game.Players.LocalPlayer.Character 

									end
								end
							end
						end)
					end
				end
			end 
		end

		local W1Paragraph = BypassedToolsSelection:AddParagraph({
			Title = "Warning!",
			Content = "The gregsHammer has a few conditions: You have to have a good pickaxe/axe! (Recommendation: Opal) | Have Fun :)"
		})

		local W2Paragraph = BypassedToolsSelection:AddParagraph({
			Title = "How to use?",
			Content = "(before you click on the gregsHammer you have to equip a tool that you want to bypass!) | it doesn't bypass the Cooldown just gives you the Effect of the gregsHammer"
		})

		-- After you have pressed a button, you have to equip another item of your choice

		BypassedToolsSelection:AddButton({
			Title = "Get forgeHammer (Works!) [BYPASSED]",
			Description = "",
			Callback = function()
				if game.Players.LocalPlayer.Character:FindFirstChild("forgeHammer") == nil and game.Players.LocalPlayer.Backpack:FindFirstChild("forgeHammer") == nil then
					GetTool("forgeHammer")
				else
					Message("😎", "You got the forgeHammer Already!", "xD", "Woah")
				end
			end
		})

		BypassedToolsSelection:AddButton({
			Title = "Get gregsHammer (READ [How to use?] and [Warning!])",
			Description = "",
			Callback = function()
				if game.Players.LocalPlayer.Character:FindFirstChild("gregsHammer") == nil and game.Players.LocalPlayer.Backpack:FindFirstChild("gregsHammer") == nil then
					if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") then
						if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool"):FindFirstChild("axe") then
							GetTool("gregsHammer", true, game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool").Name)
						else
							Message("😳", "You can Only Bypass Axes and Pickaxes :)", "hehe", "Woah")
						end
					else
						Message("🤪", "equip the tool you want to bypass first!", "Ok :)))", "Woah")
					end
				else
					Message("😎", "You got the gregsHammer Already!", "xD", "Woah")
				end
			end
		})

		BypassedToolsSelection:AddButton({
			Title = "Get crystallinePlow (READ [How to use?] and [Warning!])",
			Description = "",
			Callback = function()
				if game.Players.LocalPlayer.Character:FindFirstChild("crystallinePlow") == nil and game.Players.LocalPlayer.Backpack:FindFirstChild("crystallinePlow") == nil then
					if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") or game.Players.LocalPlayer.Backpack:FindFirstChild("hoe") then
						local TOOL =  game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") or game.Players.LocalPlayer.Backpack:FindFirstChild("hoe") 
						if TOOL:FindFirstChild("hoe") then
							GetTool("crystallinePlow", true, TOOL.Name)
							task.wait()
							TOOL.Parent = game.Players.LocalPlayer.Character
							task.wait()
							TOOL.Parent = game.Players.LocalPlayer.Backpack
						else
							Message("😳", "You can Only Bypass Plows :)", "hehe", "Woah")
						end
					else
						Message("🤪", "equip the tool you want to bypass first!", "Ok :)))", "Woah")
					end
				else
					Message("😎", "You got the crystallinePlow Already!", "xD", "Woah")
				end
			end
		})

		function SecretHammer()		
			local player = game.Players.LocalPlayer
			local mouse = player:GetMouse()

			local Tool = Instance.new("Tool", game:GetService("ReplicatedStorage"))
			local Handle = Instance.new("Part", Tool)
			Tool.PrimaryPart = Handle
			Handle.CanCollide = false
			local Mesh = Instance.new("SpecialMesh", Handle)
			Mesh.MeshId = "http://www.roblox.com/asset/?id=12592754"
			Mesh.MeshType = Enum.MeshType.FileMesh
			Mesh.TextureId = "http://www.roblox.com/asset/?id=12592745"

			local hammerModel = Tool

			local throwForce = 80
			local returnSpeed = 70
			local intervalDistance = 3
			local maxDistance = 40

			local function throwHammer()
				if _G.UseSecretHammer == true then
					local hammer = hammerModel:Clone()
					hammer.Parent = game.Workspace

					local character = player.Character
					if character then
						local characterRoot = character:FindFirstChild("HumanoidRootPart")
						if characterRoot then
							local camera = game.Workspace.CurrentCamera
							local ray = camera:ScreenPointToRay(mouse.X, mouse.Y)
							local throwDirection = ray.Direction

							local normalizedThrowDirection = Vector3.new(throwDirection.X, 0, throwDirection.Z).unit

							hammer:SetPrimaryPartCFrame(CFrame.new(characterRoot.Position))
							local hammerVelocity = normalizedThrowDirection * throwForce

							local bodyVelocity = Instance.new("BodyVelocity")
							bodyVelocity.Velocity = hammerVelocity
							bodyVelocity.MaxForce = Vector3.new(math.huge, math.huge, math.huge)
							bodyVelocity.Parent = hammer.PrimaryPart

							local lastPosition = hammer.PrimaryPart.Position
							local distanceTraveled = 0

							while hammer.Parent and distanceTraveled < maxDistance do
								local newPosition = hammer.PrimaryPart.Position
								local stepDistance = (newPosition - lastPosition).Magnitude

								distanceTraveled = distanceTraveled + stepDistance

								if stepDistance >= intervalDistance then
									local direction = (newPosition - lastPosition).unit
									local distanceBetweenPoints = stepDistance

									for distance = intervalDistance, distanceBetweenPoints, intervalDistance do
										local positionOnPath = lastPosition + direction * distance
										local roundedPosition = Vector3.new(
											math.floor(positionOnPath.X / intervalDistance) * intervalDistance,
											math.floor(positionOnPath.Y / intervalDistance) * intervalDistance,
											math.floor(positionOnPath.Z / intervalDistance) * intervalDistance
										)

										if game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool") then

											local args = {
												[1] = {
													["upperBlock"] = false,
													["cframe"] = CFrame.new(roundedPosition), -- CFrame.new(Vector3.new(pos.x, pos.y, pos.z, 1, 0, 0, 0, 1, 0, 0, 0, 1))
													["blockType"] = game.Players.LocalPlayer.Character:FindFirstChildWhichIsA("Tool").Name,
													[CropPlaceH1] = CropPlaceH2
												}
											}

											game:GetService("ReplicatedStorage"):WaitForChild("rbxts_include"):WaitForChild("node_modules"):WaitForChild("@rbxts"):WaitForChild("net"):WaitForChild("out"):WaitForChild("_NetManaged"):WaitForChild("CLIENT_BLOCK_PLACE_REQUEST"):InvokeServer(unpack(args))

											print("Remote sent!")

										end


										print("Hammer Position:", roundedPosition)
										local Part = Instance.new("Part", nil)
										Part.Anchored = true
										Part.Size = Vector3.new(3, 3, 3)
										Part.Position = roundedPosition
									end

									lastPosition = newPosition
								end

								wait(0.1)
							end

							if hammer.Parent then
								local returnDirection = (characterRoot.Position - hammer.PrimaryPart.Position).unit
								local returnVelocity = returnDirection * returnSpeed
								bodyVelocity.Velocity = returnVelocity

								repeat wait(0.1)

									local returnDirection = (characterRoot.Position - hammer.PrimaryPart.Position).unit
									local returnVelocity = returnDirection * returnSpeed
									bodyVelocity.Velocity = returnVelocity

								until (hammer.PrimaryPart.Position - characterRoot.Position).Magnitude <= 10

								bodyVelocity:Destroy()
								hammer:Destroy()
							end
						end
					end
				end
			end

			mouse.Button1Down:Connect(throwHammer)

		end


		local TimesClicked = 0
		local GotSecretButton = false
		local HaveFunSecretButton

		local BypassedProblemsSelection = Tabs.BypassFun:AddSection("Problems with the Bypasses?")

		local BypassedProblemsButton = BypassedProblemsSelection:AddParagraph({
			Title = "Problems?",
			Content = "Report Problems to the Discord!"
		})

		BypassedProblemsSelection:AddButton({
			Title = "Have Fun 🤯",
			Description = "",
			Callback = function()
				if TimesClicked > 14 then
					if GotSecretButton == false then
						SecretHammer()
						GotSecretButton = true

						local SuperSecretProHammerSelection = Tabs.BypassFun:AddSection("Super Secret Pro Hammer")

						local GetSuperSecretProHammer = SuperSecretProHammerSelection:AddToggle("GetSuperSecretProHammer", {Title = "Secret Pro Hammer 😨", Default = false })

						GetSuperSecretProHammer:OnChanged(function(Value)
							_G.UseSecretHammer = Value
						end)

					end
				else
					TimesClicked = TimesClicked + 1
				end
			end
		})

	else
		--local Section = Tab:CreateSection("Fun [BETA!]")
		-- Paragraph = Tab:CreateParagraph({Title = "Premium only!", Content = ""})



		local BypassedProblemsButton = Tabs.BypassFun:AddParagraph({
			Title = "Premium only!",
			Content = PremiumText1
		})


	end

	local IslandFarmSelection = Tabs.Other:AddSection("Island Farm")

	_G.Island_USERID = game.Players.LocalPlayer.UserId

	local UserIdLabel = IslandFarmSelection:AddParagraph({
		Title = "UserId:",
		Content = game.Players.LocalPlayer.UserId
	})

	local Input = IslandFarmSelection:AddInput("Input", {
		Title = "Username to Farm",
		Default = game.Players.LocalPlayer.Name,
		Placeholder = game.Players.LocalPlayer.Name,
		Numeric = false, -- Only allows numbers
		Finished = false, -- Only calls callback when you press enter
		Callback = function(Text)
			if Text == nil or Text == "" or Text == " " then return nil end
			local ID = game:GetService("Players"):GetUserIdFromNameAsync(Text) 
			if not ID then return nil end 
			_G.Island_USERID = ID
			UserIdLabel:SetDesc("UserId: ".._G.Island_USERID.." ("..Text..")")
		end
	})

	local Input = IslandFarmSelection:AddInput("Input", {
		Title = "Userid to Farm",
		Default = game.Players.LocalPlayer.UserId,
		Placeholder = game.Players.LocalPlayer.UserId,
		Numeric = true, -- Only allows numbers
		Finished = false, -- Only calls callback when you press enter
		Callback = function(ID)
			if not ID then return nil end
			_G.Island_USERID = ID
			UserIdLabel:Set("UserId: ".._G.Island_USERID)
		end
	})

	local Portal

	local RemovePortal = IslandFarmSelection:AddToggle("RemovePortal", {Title = "Remove Portal", Default = false })

	RemovePortal:OnChanged(function(Value)
		if not Portal or Portal.Parent ~= GetIsland():FindFirstChild("Blocks") then
			print("No Portal set... Getting!")
			local Island = GetIsland()
			if Island and Island:FindFirstChild("Blocks") then
				for i,v in pairs(Island:FindFirstChild("Blocks"):GetChildren()) do 
					if v:FindFirstChild("PortalActive") and v:FindFirstChild("portal-to-spawn") then
						Portal = v
					end
				end 
			end 
		end
		if Value == true then
			local Island = GetIsland()
			if Island and Island:FindFirstChild("Blocks") then
				local Portal = Island:FindFirstChild("Blocks"):FindFirstChild("portalToSpawn")
				if Portal then
					Portal.Parent = game
				end
			end 
		else
			local Island = GetIsland()
			if Island and Island:FindFirstChild("Blocks") then
				local Portal = game:FindFirstChild("portalToSpawn")
				if Portal then
					Portal.Parent = Island:FindFirstChild("Blocks")
				end
			end 
		end
	end)

	local OtherSelection = Tabs.Other:AddSection("Other")


	OtherSelection:AddButton({
		Title = "Read all Mails",
		Description = "",
		Callback = function()
			for i = 1,1000 do
				local args = {
					[1] = "game_update_"..i
				}

				game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged:FindFirstChild("Mailbox/ReadMail"):FireServer(unpack(args))

				task.wait()    
			end
		end
	})

	OtherSelection:AddButton({
		Title = "No Fog",
		Description = "",
		Callback = function()
			_G.NoFog = true
			Message("Success!", "Anti Fog got successfully Enabled!", "Nice!", 1)
		end
	})

	OtherSelection:AddButton({
		Title = "Kick all NPCS",
		Description = "",
		Callback = function()
			Window:Dialog({
				Title = "Are you sure?",
				Content = "",
				Buttons = {
					{
						Title = "Confirm",
						Callback = function()
							local Island = GetIsland()
							local Entities = Island:FindFirstChild("Entities") 
							if Entities then
								for i,v in pairs(Entities:GetChildren()) do
									if v:FindFirstChild("VillagerID") then
										game:GetService("ReplicatedStorage"):WaitForChild("rbxts_include"):WaitForChild("node_modules"):WaitForChild("@rbxts"):WaitForChild("net"):WaitForChild("out"):WaitForChild("_NetManaged"):WaitForChild("RequestVillagerLeave"):FireServer(v)
									end
								end
							end
						end
					},
					{
						Title = "Cancel",
						Callback = function()

						end
					}
				}
			})
		end
	})


	local AutoPickupTools = OtherSelection:AddToggle("AutoPickupTools", {Title = "Auto Pickup Tools", Default = false })

	AutoPickupTools:OnChanged(function(Value)
		if Value == true then
			_G.AutoPickupItems = true
		else
			_G.AutoPickupItems = false
		end
	end)

	local CleanIslandToggle = OtherSelection:AddToggle("CleanIsland", {Title = "Clean Island", Default = false })

	CleanIslandToggle:OnChanged(function(Value)
		if Value == true then
			_G.AutoCleanIsland = true
		else
			_G.AutoCleanIsland = false
		end
	end)



	local FlowerSelection = Tabs.Other:AddSection("Flower")

	local FlowerAutoFarm = FlowerSelection:AddToggle("FlowerAutoFarm", {Title = "Flower Auto Farm", Default = false })

	FlowerAutoFarm:OnChanged(function(Value)
		if Value == true then
			_G.flowerFarm = true
		else
			_G.flowerFarm = false
		end
	end)

	local FlowerAura = FlowerSelection:AddToggle("FlowerAura", {Title = "Flower Aura", Default = false })

	FlowerAura:OnChanged(function(Value)
		if Value == true then
			_G.flowerAura = true
		else
			_G.flowerAura = false
		end
	end)

	local PlowSelection = Tabs.Other:AddSection("Plow Island")

	local PlowAuraToggle = PlowSelection:AddToggle("PlowAura", {Title = "Plow Aura", Default = false })

	PlowAuraToggle:OnChanged(function(Value)
		if Value == true then
			_G.PlowAura = true
		else
			_G.PlowAura = false
		end
	end)

	local unPlowAuraToggle = PlowSelection:AddToggle("unPlowAura", {Title = "unPlow Aura", Default = false })

	unPlowAuraToggle:OnChanged(function(Value)
		if Value == true then
			_G.UnPlowAura = true
		else
			_G.UnPlowAura = false
		end
	end)

	local PlowDistanceSlider = PlowSelection:AddSlider("PlowDistanceSlider", {
		Title = "Plow Distance",
		Description = "",
		Default = 10,
		Min = 1,
		Max = 35,
		Rounding = 0,
		Callback = function(Value)
			_G.PlowDistance = Value
		end
	})


	local CropPlaceAuraSelection = Tabs.Other:AddSection("Crop Place Aura")

	local CropPlaceAura = CropPlaceAuraSelection:AddToggle("CropPlaceAura", {Title = "Crop Place Aura", Default = false })

	CropPlaceAura:OnChanged(function(Value)
		if Value == true then
			_G.AuraAuraPlace = true
		else
			_G.AuraAuraPlace = false
		end
	end)

	local CropPlaceAuraDistance = CropPlaceAuraSelection:AddSlider("CropPlaceAuraDistance", {
		Title = "Crop Distance",
		Description = "",
		Default = 25,
		Min = 1,
		Max = 25,
		Rounding = 0,
		Callback = function(Value)
			_G.PlaceCropsMaxArea = Value
		end
	})

	local AnimalSelection = Tabs.Other:AddSection("Pets/Animals")

	local AnimalAutoFarm = AnimalSelection:AddToggle("AnimalAutoFarm", {Title = "Pet Auto Farm", Default = false })

	AnimalAutoFarm:OnChanged(function(Value)
		if Value == true then
			_G.PET_ANIMALFarm = true
		else
			_G.PET_ANIMALFarm = false
		end
	end)


	local AnimalAura = AnimalSelection:AddToggle("AnimalAura", {Title = "Pet Aura", Default = false })

	AnimalAura:OnChanged(function(Value)
		if Value == true then
			_G.PET_ANIMALAura = true
		else
			_G.PET_ANIMALAura = false
		end
	end)


	local BankSelection = Tabs.Other:AddSection("Bank")

	local DeposittoBank = BankSelection:AddInput("DeposittoBank", {
		Title = "Deposit to Bank",
		Default = "0",
		Placeholder = "0",
		Numeric = true, -- Only allows numbers
		Finished = true, -- Only calls callback when you press enter
		Callback = function(Value)
			local args = {
				[1] = Hash(),
				[2] = {
					[1] = {
						["accountType"] = "PERSONAL",
						["transferType"] = "DEPOSIT",
						["amount"] = tonumber(Value)
					}
				}
			}

			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.TransactionBankBalance:FireServer(unpack(args))	
		end
	})

	local WithdrawFromBank = BankSelection:AddInput("WithdrawFromBank", {
		Title = "Withdraw From Bank",
		Default = "0",
		Placeholder = "0",
		Numeric = true, -- Only allows numbers
		Finished = true, -- Only calls callback when you press enter
		Callback = function(Value)
			local args = {
				[1] = Hash(),
				[2] = {
					[1] = {
						["accountType"] = "PERSONAL",
						["transferType"] = "WITHDRAWAL",
						["amount"] = tonumber(Value)
					}
				}
			}

			game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.TransactionBankBalance:FireServer(unpack(args))	
		end
	})

	local ScriptSettingsSelection = Tabs.Settings:AddSection("Script Settings")


	local TeleportMethod = ScriptSettingsSelection:AddDropdown("TeleportMethod", {
		Title = "Teleport Method",
		Values = {"Tween","TweenV3", "MiniTp", "Instant", "Pathfinding", "PathfindingV2"},
		Multi = false,
		Default = 1,
	})


	TeleportMethod:OnChanged(function(Value)
		_G.TeleportMethod = Value
	end)

	ScriptSettingsSelection:AddButton({
		Title = "Stop Gay Tween",
		Description = "",
		Callback = function()
			if LASTTWEEN == nil then
				-- warn("Tween ist nil!")
			else
				LASTTWEEN:Cancel()
			end
		end
	})

	local DisableXP = ScriptSettingsSelection:AddToggle("DisableXP", {Title = "Disable XP [ANTI LAG!]", Default = false })

	DisableXP:OnChanged(function(Value)
		local LocalPlayer = game.Players.LocalPlayer
		if Value == true then
			LocalPlayer.PlayerScripts.TS.modules.experience["experience-listener"].Disabled = true
		else
			LocalPlayer.PlayerScripts.TS.modules.experience["experience-listener"].Disabled = false
		end
	end)

	local originalValues = {}

	local AntilagV1L

	local Lighting = game:GetService("Lighting")

	local function AntiLag()
		local PCALL = pcall(function()
			-- Speichere die ursprünglichen Werte der Eigenschaften

			local Terrain = workspace:FindFirstChildOfClass('Terrain')
			originalValues.TerrainWaterWaveSize = Terrain.WaterWaveSize
			originalValues.TerrainWaterWaveSpeed = Terrain.WaterWaveSpeed
			originalValues.TerrainWaterReflectance = Terrain.WaterReflectance
			originalValues.TerrainWaterTransparency = Terrain.WaterTransparency

			originalValues.LightingGlobalShadows = Lighting.GlobalShadows
			originalValues.LightingFogEnd = Lighting.FogEnd
			originalValues.RenderingQualityLevel = settings().Rendering.QualityLevel

			for i, v in pairs(game.Workspace:GetDescendants()) do

				if v:IsA("MeshPart") and v.Parent and v.Parent.Name == "wheat" then

					print(v.Name)
					originalValues[v] = {
						Material = v.Material,
						Reflectance = v.Reflectance,
						MeshId = v.MeshId
					}
					v.Material = Enum.Material.Plastic
					v.Reflectance = 0
					v.MeshId = 0

				elseif v:IsA("BasePart") or v:IsA("UnionOperation") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then 


					if v.Name == "stage-3" then
						print(v.Name)
					end
					originalValues[v] = {
						Material = v.Material,
						Reflectance = v.Reflectance
					}
					v.Material = Enum.Material.Plastic
					v.Reflectance = 0

				elseif v:IsA("Decal") then
					originalValues[v] = {
						Transparency = v.Transparency
					}
					v.Transparency = 1
				elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
					originalValues[v] = {
						Lifetime = v.Lifetime
					}
					v.Lifetime = NumberRange.new(0)
				elseif v:IsA("Explosion") then
					originalValues[v] = {
						BlastPressure = v.BlastPressure,
						BlastRadius = v.BlastRadius
					}
					v.BlastPressure = 1
					v.BlastRadius = 1
				end

			end

			for i, v in pairs(Lighting:GetDescendants()) do
				if v:IsA("BlurEffect") or v:IsA("SunRaysEffect") or v:IsA("ColorCorrectionEffect") or v:IsA("BloomEffect") or v:IsA("DepthOfFieldEffect") then
					originalValues[v] = {
						Enabled = v.Enabled
					}
					v.Enabled = false
				end
			end

			-- Überwache neue Kinder im Workspace und entferne bestimmte Elemente

			local function handleDescendantAdded(child)
				coroutine.wrap(function()
					local v = child
					if v:IsA("MeshPart") and v.Parent and v.Parent.Name == "wheat" then
						originalValues[v] = {
							Material = v.Material,
							Reflectance = v.Reflectance,
							MeshId = v.MeshId
						}
						v.Material = Enum.Material.Plastic
						v.Reflectance = 0
						v.MeshId = 0
					elseif child:IsA('ForceField') then
						task.wait()
						child:Destroy()
					elseif child:IsA('Sparkles') then
						task.wait()
						child:Destroy()
					elseif child:IsA('Smoke') or child:IsA('Fire') then
						task.wait()
						child:Destroy()
					end
				end)()
			end

			AntilagV1L = workspace.DescendantAdded:Connect(handleDescendantAdded)
		end)
	end

	local function UndoAntiLag()
		local Pcall = pcall(function()
			-- Stelle die ursprünglichen Werte der Eigenschaften wieder her

			local Terrain = workspace:FindFirstChildOfClass('Terrain')
			Terrain.WaterWaveSize = originalValues.TerrainWaterWaveSize
			Terrain.WaterWaveSpeed = originalValues.TerrainWaterWaveSpeed
			Terrain.WaterReflectance = originalValues.TerrainWaterReflectance
			Terrain.WaterTransparency = originalValues.TerrainWaterTransparency

			Lighting.FogEnd = originalValues.LightingFogEnd
			settings().Rendering.QualityLevel = originalValues.RenderingQualityLevel

			for i, v in pairs(game.Workspace:GetDescendants()) do
				if originalValues[v] then
					if v:IsA("MeshPart") and v.Parent and v.Parent.Name == "wheat"  then

						v.Material = originalValues[v].Material
						v.Reflectance = originalValues[v].Reflectance
						v.MeshId = originalValues[v].MeshId


					elseif  v:IsA("BasePart") or v:IsA("UnionOperation") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then
						v.Material = originalValues[v].Material
						v.Reflectance = originalValues[v].Reflectance
					elseif v:IsA("Decal") then
						v.Transparency = originalValues[v].Transparency
					elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
						v.Lifetime = originalValues[v].Lifetime
					elseif v:IsA("Explosion") then
						v.BlastPressure = originalValues[v].BlastPressure
						v.BlastRadius = originalValues[v].BlastRadius
					end
					originalValues[v] = nil
				end
			end

			for i, v in pairs(Lighting:GetDescendants()) do
				if originalValues[v] then
					v.Enabled = originalValues[v].Enabled
					originalValues[v] = nil
				end
			end


			if AntilagV1L then
				AntilagV1L:Disconnect()
			end
		end)
	end




	ScriptSettingsSelection:AddButton({
		Title = "Stop Script",
		Description = "",
		Callback = function()
			if MAINSCRIPTHANDLER ~= nil then
				MAINSCRIPTHANDLER:Disconnect()
			end
		end
	})

	local FlyKeyBind = ScriptSettingsSelection:AddKeybind("FlyKeyBind", {
		Title = "Fly Key",
		Mode = "Toggle", -- Always, Toggle, Hold
		Default = "G", -- String as the name of the keybind (MB1, MB2 for mouse buttons)

		-- Occurs when the keybind is clicked, Value is `true`/`false`
		Callback = function(Value)
			if game.Players.LocalPlayer.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("BodyVelocity") then
				PlayerFly:SetValue(false)
			else
				PlayerFly:SetValue(true)
			end
		end,

		-- Occurs when the keybind itself is changed, `New` is a KeyCode Enum OR a UserInputType Enum
		ChangedCallback = function(New)
			print("Keybind changed!", New)
		end
	})


	local ColorSettingsSelection = Tabs.Settings:AddSection("Color Settings")

	local ResizeToolOutlineColor = ColorSettingsSelection:AddColorpicker("ResizeToolOutlineColor", {
		Title = "ResizeToolOutlineColor",
		Default = Color3.fromRGB(225, 0, 0)
	})

	ResizeToolOutlineColor:OnChanged(function(Value)
		_G.ResizeToolOutlineColor = Value
	end)

	local ResizeToolMoveButtons = ColorSettingsSelection:AddColorpicker("ResizeToolMoveButtons", {
		Title = "ResizeToolMoveButtons",
		Default = Color3.fromRGB(254, 254, 254)
	})

	ResizeToolMoveButtons:OnChanged(function(Value)
		_G.ResizeToolMoveButtonColor = Value
	end)

	local ResizeToolFillColor = ColorSettingsSelection:AddColorpicker("ResizeToolFillColor", {
		Title = "Resize Tool FillColor",
		Description = "",
		Transparency = 0,
		Default = Color3.fromRGB(96, 205, 255),
	})

	ResizeToolFillColor:OnChanged(function()
		_G.ResizeToolFillColor = ResizeToolFillColor.Value
		_G.ResizeToolFillTransparency = ResizeToolFillColor.Transparency
	end)


	_G.TweenFlySpeed = 25

	_G.RockTarget = "Stone"
	_G.RockFarmSpeed = 25
	_G.AutoReplaceCrop = true
	_G.SelectedTree = "all"
	_G.SelectedMob = "slime"
	_G.SelectedCrop = "wheat"
	_G.CropAura_BETA = false
	_G.UseSichle = true
	_G.SichleCropDelay = 13
	_G.SichleCropRange = 30
	_G.WalkSpeed = 30
	_G.JumpPower = 50
	_G.TeleportMethod = "Tween"
	_G.UseSichleTool = "sickleStone"
	_G.PET_ANIMALFarm = false
	_G.PET_ANIMALAura = false
	_G.PlowDistance = 10
	_G.FastBlockPrinter = true
	_G.Place3 = false
	_G.PlayerBlockPrinterSpeed = 5
	_G.BlockPrinterTP = true
	_G.Island_USERID = game.Players.LocalPlayer.UserId
	_G.SelectedBoss = "slimeKing"
	_G.MobTpYPos = 8
	_G.SafeUseSichle = true
	_G.SuperFastCropFarm = false
	_G.RemotesToSendToDestroy = 3
	_G.PlaceCropsMaxArea = 30

	_G.CheckPrintedBlocks = true

	_G.SelectedTotem = "totemWheat"
	_G.SelectedUpgrade = "utility"
	_G.TotemLevel = 25
	_G.AutoUpgradeTotem = false 

	_G.ResizeToolOutlineColor = Color3.fromRGB(225, 0, 0)

	_G.ResizeToolMoveButtonColor = Color3.fromRGB(254, 254, 254)

	_G.ResizeToolFillTransparency = 1
	_G.ResizeToolFillColor = Color3.fromRGB(225, 225, 225)

	local MainCooldown = false
	local CB = false

	local FM = false
	local ReplaceCooldown = false

	game:GetService("RunService").RenderStepped:Connect(function()
		local Character = game.Players.LocalPlayer.Character 
		if Character then
			local Humanoid = Character:FindFirstChild("Humanoid")
			if Humanoid then
				Humanoid.WalkSpeed = _G.WalkSpeed or 30
				Humanoid.JumpPower = _G.JumpPower or 50
			end
		end
	end)



	MAINSCRIPTHANDLER = game:GetService("RunService").RenderStepped:Connect(function()

		if _G.NoFog == true then
			local Lighting = game:GetService("Lighting")
			Lighting.FogEnd = 100000
			for i,v in pairs(Lighting:GetDescendants()) do
				if v:IsA("Atmosphere") then
					v:Destroy()
				end
			end
		end

		-- Event --

		-- Event --


		if _G.AutoFarm == true then
			if FM == false then
				FM = true
				FarmMob()
				--task.wait(0.1)
				FM = false
			end
		else
			_G.MobRemoteSpamming = false
			if _G.DoubleAutoFarm == true then
				DoubleFarmMob()
			end
		end



		if _G.BossAutoFarm == true then
			BossCheck(_G.SelectedBoss)
		end

		if _G.MobKillAura == true then
			KillAura()
		end

		if _G.voidParasiteFarm == true then
			voidParasiteFarm(true)
		end

		if _G.SpiritAutoFarmBool == true then
			spiritFarm(true)
		end



		if _G.AuraAuraPlace == true then
			SeedAura()
		end

		if _G.PET_ANIMALFarm == true then
			PET_ANIMALFarm(true)
		end

		if _G.PET_ANIMALAura == true then
			PET_ANIMALFarm(false)
		end

		if _G.flowerAura == true  then
			flowerFarm(false)
		end

		if _G.PlowAura == true  then
			if PLAC == false then -- funktion cooldown wegen lag
				PlowAura(true)
			end
		end


		if _G.UnPlowAura == true then -- funktion cooldown wegen lag
			if PLAC == false then
				PlowAura(false)
			end
		end

		if _G.flowerFarm == true  then
			flowerFarm(true)
		end

		if _G.CropAutoFarm == true then
			if _G.UseSichle == true then
				if SichleFarmCooldown == false then
					SichleFarmCooldown = true
					local LocalPlayer = game.Players.LocalPlayer
					SichleCropFarm(true)
				end
			else
				local LocalPlayer = game.Players.LocalPlayer
				CropFarm(true)
			end

		end

		if _G.CropAura_BETA == true then
			if _G.UseSichle == true then
				if SichleAuraCooldown == false then
					SichleAuraCooldown = true
					local LocalPlayer = game.Players.LocalPlayer
					SichleCropFarm(false)
				end
			else
				local LocalPlayer = game.Players.LocalPlayer
				CropFarm(false)
			end
		end


		if _G.TreeAutoFarm == true then
			TreeFarm(true)
		end	

		if _G.TreeAura == true then
			TreeFarm(false)
			-- TreeAura()
		end

		if _G.FishFarm == true then
			FishFarm()
		end

		if _G.ChestAura == true then
			ChestAura()
		end

		if _G.AutoCollectFruits == true then
			AutoCollectFruits()
		end

		if _G.RockAutoFarm == true then
			RockFarmV2(_G.RockTarget or "Stone", true)
		end


		if _G.RockFarmonIsland == true then
			RockFarmV2(_G.RockTargetonIsland or "Stone", true)
		end

		if _G.RockAura == true then
			RockAura()
		end

		if _G.AutoPickupItems == true then
			AutoPickupItems()
		end

		if _G.AutoCleanIsland == true then
			CleanIsland()
		end

		-- TOTEM --


		if _G.AutoCollectTotemItems == true then
			AutoCollectTotemItems()
		end

		if 	_G.AutoUpgradeTotem == true then

			-- Funktion zum Finden des nächsten Teils
			local function findNearestPart(A)
				local closestPart = nil
				local closestDistance = math.huge
				local playerPosition = game.Players.LocalPlayer.Character.HumanoidRootPart.Position

				local Table = A

				for i, part in ipairs(Table) do
					local distance = (part.Position - playerPosition).magnitude
					if distance < closestDistance then
						closestPart = part
						closestDistance = distance
					end
				end

				DebugCheck(0,"findNearestPart")

				return closestPart
			end

			local Island = GetIsland()

			local Totems = {}

			for i,v in ipairs(Island:FindFirstChild("Blocks"):GetChildren()) do
				if v.Name == _G.SelectedTotem then

					if v:FindFirstChild("UpgradeProgress"):FindFirstChild(_G.SelectedUpgrade) then
						if v:FindFirstChild("UpgradeProgress"):FindFirstChild(_G.SelectedUpgrade).Value <= _G.TotemLevel then
							table.insert(Totems, v)
							task.wait()
						else
							DebugCheck(0,"Level erreicht!")
							return nil 
						end
					else 
						DebugCheck(0,"UpgradeProgress not found!")
						return nil 
					end
				end
			end

			local NearestTotem = findNearestPart(Totems)

			print("Nearest:",NearestTotem)

			local v = NearestTotem

			while NearestTotem and v:FindFirstChild("UpgradeProgress") and v:FindFirstChild("UpgradeProgress"):FindFirstChild(_G.SelectedUpgrade).Value < _G.TotemLevel do

				if _G.AutoUpgradeTotem == false then 
					return nil 
				end


				local Distance = (v.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude

				if Distance > 10 then
					print("Distance Kleiner als 20")
					TeleportV4(v.Position)
					repeat wait() TeleportV4(v.Position) until (v.Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position).Magnitude < 9 
				end


				local ohInstance1 = v
				local ohString2 = GetName(v.Name)
				local ohString3 = _G.SelectedUpgrade

				game:GetService("ReplicatedStorage").rbxts_include.node_modules["@rbxts"].net.out._NetManaged.UpgradeBlock:InvokeServer(ohInstance1, ohString2, ohString3)


			end

		end -- abfrage

		-- TOTEM --

	end)


	SaveManager:SetLibrary(Fluent)
	InterfaceManager:SetLibrary(Fluent)

	-- Ignore keys that are used by ThemeManager.
	-- (we dont want configs to save themes, do we?)
	SaveManager:IgnoreThemeSettings()

	-- You can add indexes of elements the save manager should ignore
	SaveManager:SetIgnoreIndexes({})

	-- use case for doing it this way:
	-- a script hub could have themes in a global folder
	-- and game configs in a separate folder per game
	InterfaceManager:SetFolder("Nekohub/Islands")
	SaveManager:SetFolder("Nekohub/Islands")

	InterfaceManager:BuildInterfaceSection(Tabs.Settings)
	SaveManager:BuildConfigSection(Tabs.Settings)


	Window:SelectTab(1)

	Fluent:Notify({
		Title = "Fluent",
		Content = "The script has been loaded.",
		Duration = 8
	})

	SaveManager:LoadAutoloadConfig()

	print("Script Loaded!")





	-- end
