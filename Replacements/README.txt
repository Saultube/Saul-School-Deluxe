This README contains all of the valid replacements you could do!
Valid classes and fields:
RectTransform:
	anchoredPosition
	anchoredPostion3D
	sizeDelta
	pivot
	offsetMin
	offsetMax
	anchorMin
	anchorMax
	localPosition
	position
	localScale
	rotation
	eulerAngles
	localEulerAngles
	localRotation
Transform:
	localPosition
	position
	localScale
	rotation
	eulerAngles
	localEulerAngles
	localRotation
Fog:
	color
	maxDist
	startDist
	strength
LineRenderer:
	widthMultiplier
	textureMode
TMP_Text:
	color
	fontStyle
	text
	alignment
TextLocalizer:
	key
TextMeshPro:
	color
	fontStyle
	text
	alignment
TextMeshProUGUI:
	color
	fontStyle
	text
	alignment
Image:
	color
HardcodedTexturePackReplacements:
	BSODAShouldRotate
	ItemSlotBackgroundColor
	ItemSlotHighlightColor
CursorInitiator:
	cursorColor
SpriteRenderer:
	color
RawImage:
	color
FloodEvent:
	underwaterFog
FogEvent:
	fogColor
Valid Root Objects (Objects at the top/root of the replacement file):
	HardcodedTexturePackReplacements:BepInEx_Manager
	MathMachine:MathMachine_Corner
	MathMachine:MathMachine
	BalloonBuster:Activity_BalloonBuster
	BalloonBusterBalloon:BusterBalloon_6
	BalloonBusterBalloon:BusterBalloon_1
	BalloonBusterBalloon:BusterBalloon_2
	BalloonBusterBalloon:BusterBalloon_3
	BalloonBusterBalloon:BusterBalloon_5
	BalloonBusterBalloon:BusterBalloon_7
	BalloonBusterBalloon:BusterBalloon_4
	BalloonBusterBalloon:BusterBalloon_0
	MatchActivityBalloon:MatchBalloon_0
	FloodEvent:Event_Flood
	FogEvent:Event_Fog
	HudManager:MainHud
	HudManager:AuthenticModeCanvas
	LookAtGuy:LookAt
	DigitalClock:DigitalClock_1
	DigitalClock:DigitalClock
	DigitalClock:DetentionTimer
	DigitalClock:DigitalClock_1
	DigitalClock:DigitalClock
	DigitalClock:DigitalClock
	DigitalClock:Timer
	ElevatorScreen:ElevatorScreen
	Item:Alarm Clock
	Item:Boots
	Item:ITM_BSODA
	Item:ITM_DietBSODA
	Item:ChalkEraser
	Item:DetentionKey
	Item:GrapplingHook
	Item:NoSquee
	Item:Quarter
	Item:ITM_ZestyBar
	Item:SwingDoorLock
	Item:Tape
	Item:Nametag
	Item:Scissors
	Item:ITM_None
	Item:Teleporter
	Item:PortalPoster
	Item:NanaPeel
	Item:PrincipalWhistle
	Item:ReachExtender
	Item:InvisibilityElixir
	Item:LostItem_0
	Item:LostItem_1
	Item:LostItem_2
	Item:LostItem_3
	Item:LostItem_4
	Item:LostItem_5
	Item:LostItem_6
	Item:LostItem_7
	Item:LostItem_8
	Item:LostItem_9
	Item:GrapplingHook1
	Item:GrapplingHook2
	Item:GrapplingHook3
	Item:GrapplingHook4
	Item:BusPass
	Item:GameKey_0
	Item:GameKey_1
	Item:GameKey_2
	Item:GameKey_3
	Item:GameKey_4
	Item:GameKey_5
	Item:StickerPack_Normal
	Item:ITM_Map
	Item:GlueStick
	Item:ITM_YTPs_50
	Item:ITM_YTPs_25
	Item:ITM_YTPs_100
	Item:ITM_YTPs_250
	Item:Quarter_Tutorial
	Item:StickerPack_Bonus
	Item:StickerPack_Fresh
	Item:StickerPack_Large
	Item:StickerPack_Twin
	BaldiBG:PauseScreen
	CursorInitiator:PauseScreen
Valid Transformable Objects (Objects that can have their transform positions modified):
	MathMachine_Corner->Num1 (RectTransform)
	MathMachine_Corner->Operator (RectTransform)
	MathMachine_Corner->Num2 (RectTransform)
	MathMachine_Corner->Answer (RectTransform)
	MathMachine->Num1 (RectTransform)
	MathMachine->Operator (RectTransform)
	MathMachine->Num2 (RectTransform)
	MathMachine->Answer (RectTransform)
	Activity_BalloonBuster->PulleySprite (SpriteRenderer)
	Activity_BalloonBuster->Billboard->SolutionTMP (RectTransform)
	Activity_BalloonBuster->Billboard->CountTMP  (RectTransform)
	BusterBalloon_6->RendererBase->Sprite (SpriteRenderer)
	BusterBalloon_1->RendererBase->Sprite (SpriteRenderer)
	BusterBalloon_2->RendererBase->Sprite (SpriteRenderer)
	BusterBalloon_3->RendererBase->Sprite (SpriteRenderer)
	BusterBalloon_5->RendererBase->Sprite (SpriteRenderer)
	BusterBalloon_7->RendererBase->Sprite (SpriteRenderer)
	BusterBalloon_4->RendererBase->Sprite (SpriteRenderer)
	BusterBalloon_0->RendererBase->Sprite (SpriteRenderer)
	MatchBalloon_0->RendererBase->Sprite (SpriteRenderer)
	MainHud->TestGrid (RectTransform)
	MainHud->Staminometer->Background (RectTransform)
	MainHud->Staminometer->Needle (RectTransform)
	MainHud->Staminometer->Overlay (RectTransform)
	MainHud->Staminometer (RectTransform)
	MainHud->ItemSlots->ItemSlot (0)->ItemIcon (0) (RectTransform)
	MainHud->ItemSlots->ItemSlot (0) (RectTransform)
	MainHud->ItemSlots->ItemSlot (1)->ItemIcon (1) (RectTransform)
	MainHud->ItemSlots->ItemSlot (1) (RectTransform)
	MainHud->ItemSlots->ItemSlot (2)->ItemIcon (2) (RectTransform)
	MainHud->ItemSlots->ItemSlot (2) (RectTransform)
	MainHud->ItemSlots->ItemSlot (3)->ItemIcon (3) (RectTransform)
	MainHud->ItemSlots->ItemSlot (3) (RectTransform)
	MainHud->ItemSlots->ItemSlot (4)->ItemIcon (4) (RectTransform)
	MainHud->ItemSlots->ItemSlot (4) (RectTransform)
	MainHud->ItemSlots->ItemSlot (5)->ItemIcon (5) (RectTransform)
	MainHud->ItemSlots->ItemSlot (5) (RectTransform)
	MainHud->ItemSlots->ItemSlot (6)->ItemIcon (6) (RectTransform)
	MainHud->ItemSlots->ItemSlot (6) (RectTransform)
	MainHud->ItemSlots->ItemSlot (7)->ItemIcon (7) (RectTransform)
	MainHud->ItemSlots->ItemSlot (7) (RectTransform)
	MainHud->ItemSlots->ItemSlot (8)->ItemIcon (8) (RectTransform)
	MainHud->ItemSlots->ItemSlot (8) (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_0 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_1 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_2 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_3 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_4 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_5 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_6 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_7 (RectTransform)
	MainHud->ItemSlots->Mask->ItemSlideAnimationBase (RectTransform)
	MainHud->ItemSlots->Mask (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_0 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_1 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_2 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_3 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_4 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_5 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_6 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_7 (RectTransform)
	MainHud->ItemSlots->Covers->ItemCover_8 (RectTransform)
	MainHud->ItemSlots->Covers (RectTransform)
	MainHud->ItemSlots (RectTransform)
	MainHud->Item Text (RectTransform)
	MainHud->Reticle (RectTransform)
	MainHud->NotebookIcon (RectTransform)
	MainHud->Notebook Text (RectTransform)
	MainHud->Gauges (RectTransform)
	MainHud->Baldi (RectTransform)
	MainHud->PointsDisplay->Addition (RectTransform)
	MainHud->PointsDisplay->Display->Points_TMP (RectTransform)
	MainHud->PointsDisplay->Display (RectTransform)
	MainHud->PointsDisplay (RectTransform)
	MainHud->StickerPacket->UnderStickerSprite (RectTransform)
	MainHud->StickerPacket->PacketSprite (RectTransform)
	MainHud->StickerPacket->OverStickerSprite (RectTransform)
	MainHud->StickerPacket (RectTransform)
	MainHud->BaldiTV->BaldiImage (RectTransform)
	MainHud->BaldiTV->ExclamationImage (RectTransform)
	MainHud->BaldiTV->StaticImage (RectTransform)
	MainHud->BaldiTV->TMPSkewParent->TimeTMP (RectTransform)
	MainHud->BaldiTV (RectTransform)
	MainHud->TooltipBase->Tooltip->BG (RectTransform)
	MainHud->TooltipBase->Tooltip->Tmp (RectTransform)
	MainHud->TooltipBase->Tooltip (RectTransform)
	MainHud->TooltipBase (RectTransform)
	MainHud (RectTransform)
	CoreGameManager->AuthenticModeCanvas->TvBg (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Baldi (RectTransform)
	CoreGameManager->AuthenticModeCanvas->GameView (RectTransform)
	CoreGameManager->AuthenticModeCanvas->HudView (RectTransform)
	CoreGameManager->AuthenticModeCanvas->StaminaLow->StaminaBG (RectTransform)
	CoreGameManager->AuthenticModeCanvas->StaminaLow->StaminaNeedle (RectTransform)
	CoreGameManager->AuthenticModeCanvas->StaminaLow (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items->BG (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items->Item_0 (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items->Item_1 (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items->Item_2 (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items->ItemButton_0 (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items->ItemButton_1 (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items->ItemButton_2 (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Items (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Border (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Lever (RectTransform)
	CoreGameManager->AuthenticModeCanvas->NotebookText (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Dummy->DummyImage (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Dummy->DummyRawImage (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Dummy->DummyText (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Dummy->Addition (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Dummy->TotalText (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Dummy->TotalValue (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Dummy (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Bottom->Border (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Bottom->Border (1) (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Bottom->Border (2) (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Bottom->Border (3) (RectTransform)
	CoreGameManager->AuthenticModeCanvas->Bottom (RectTransform)
	CoreGameManager->AuthenticModeCanvas (RectTransform)
	ElevatorWGate->DigitalClock_1->Display->Digit_0 (SpriteRenderer)
	ElevatorWGate->DigitalClock_1->Display->Digit_1 (SpriteRenderer)
	ElevatorWGate->DigitalClock_1->Display->Colon (SpriteRenderer)
	ElevatorWGate->DigitalClock_1->Display->Digit_2 (SpriteRenderer)
	ElevatorWGate->DigitalClock_1->Display->Digit_3 (SpriteRenderer)
	TeleporterRoomFunction->TeleporterRoomFunctionObjectBase->TeleporterMachine->DigitalClock->Display->Digit_0 (SpriteRenderer)
	TeleporterRoomFunction->TeleporterRoomFunctionObjectBase->TeleporterMachine->DigitalClock->Display->Digit_1 (SpriteRenderer)
	TeleporterRoomFunction->TeleporterRoomFunctionObjectBase->TeleporterMachine->DigitalClock->Display->Colon (SpriteRenderer)
	TeleporterRoomFunction->TeleporterRoomFunctionObjectBase->TeleporterMachine->DigitalClock->Display->Digit_2 (SpriteRenderer)
	TeleporterRoomFunction->TeleporterRoomFunctionObjectBase->TeleporterMachine->DigitalClock->Display->Digit_3 (SpriteRenderer)
	DetentionTimer->Display->Digit_0 (SpriteRenderer)
	DetentionTimer->Display->Digit_1 (SpriteRenderer)
	DetentionTimer->Display->Colon (SpriteRenderer)
	DetentionTimer->Display->Digit_2 (SpriteRenderer)
	DetentionTimer->Display->Digit_3 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock_1->Display->Digit_0 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock_1->Display->Digit_1 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock_1->Display->Colon (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock_1->Display->Digit_2 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock_1->Display->Digit_3 (SpriteRenderer)
	ElevatorWGate->DigitalClock->Display->Digit_0 (SpriteRenderer)
	ElevatorWGate->DigitalClock->Display->Digit_1 (SpriteRenderer)
	ElevatorWGate->DigitalClock->Display->Colon (SpriteRenderer)
	ElevatorWGate->DigitalClock->Display->Digit_2 (SpriteRenderer)
	ElevatorWGate->DigitalClock->Display->Digit_3 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock->Display->Digit_0 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock->Display->Digit_1 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock->Display->Colon (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock->Display->Digit_2 (SpriteRenderer)
	ElevatorWGate NoPlants->DigitalClock->Display->Digit_3 (SpriteRenderer)
	Map->Overlay->Timer->Digit_0 (Image)
	Map->Overlay->Timer->Digit_1 (Image)
	Map->Overlay->Timer->Digit_: (Image)
	Map->Overlay->Timer->Digit_2 (Image)
	Map->Overlay->Timer->Digit_3 (Image)
	ElevatorScreen->ElevatorTransission->StorePreviewBlank (RectTransform)
	ElevatorScreen->ElevatorTransission->StorePreview (RectTransform)
	ElevatorScreen->ElevatorTransission->ElDoorL (RectTransform)
	ElevatorScreen->ElevatorTransission->ElDoorR (RectTransform)
	ElevatorScreen->ElevatorTransission->Image (RectTransform)
	ElevatorScreen->ElevatorTransission->BG (RectTransform)
	ElevatorScreen->ElevatorTransission->Play (RectTransform)
	ElevatorScreen->ElevatorTransission->Lives (RectTransform)
	ElevatorScreen->ElevatorTransission->FloorIndicator (RectTransform)
	ElevatorScreen->ElevatorTransission->SeedIndicator (RectTransform)
	ElevatorScreen->ElevatorTransission->BaldiTV->BaldiImage (RectTransform)
	ElevatorScreen->ElevatorTransission->BaldiTV->ExclamationImage (RectTransform)
	ElevatorScreen->ElevatorTransission->BaldiTV->StaticImage (RectTransform)
	ElevatorScreen->ElevatorTransission->BaldiTV->TMPSkewParent->TimeTMP (RectTransform)
	ElevatorScreen->ElevatorTransission->BaldiTV (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->Sprite (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->ResultsText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->TimeText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->YTPText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->TotalText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->StickerText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->MultiplierText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->TimeValue (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->YTPValue (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->TotalValue (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->StickerValue (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->MultiplierValue (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->TimeBonusText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->TimeBonusValue (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->GradeBonusText (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen->GradeBonusValue (RectTransform)
	ElevatorScreen->ElevatorTransission->BigScreen (RectTransform)
	ElevatorScreen->ElevatorTransission->Button->ButtonLabel (RectTransform)
	ElevatorScreen->ElevatorTransission->Button->SkipButton->ButtonLabel (RectTransform)
	ElevatorScreen->ElevatorTransission->Button->SkipButton (RectTransform)
	ElevatorScreen->ElevatorTransission->Button (RectTransform)
	ElevatorScreen->ElevatorTransission->Error (RectTransform)
	ElevatorScreen->ElevatorTransission->Bottom->Border (RectTransform)
	ElevatorScreen->ElevatorTransission->Bottom->Border (1) (RectTransform)
	ElevatorScreen->ElevatorTransission->Bottom->Border (2) (RectTransform)
	ElevatorScreen->ElevatorTransission->Bottom->Border (3) (RectTransform)
	ElevatorScreen->ElevatorTransission->Bottom (RectTransform)
	ElevatorScreen->ElevatorTransission (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->StandardDescription (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (6) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->ItemBuySpot (7) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->BoughtItemSpot (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->BoughtItemSpot (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->BoughtItemSpot (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->BoughtItemSpot (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->BoughtItemSpot (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->BoughtItemSpot (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->InventorySpot (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->InventorySpot (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->InventorySpot (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->InventorySpot (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->InventorySpot (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots->InventorySpot (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Hotspots (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BG (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (0)->ItemIcon (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (1)->ItemIcon (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (2)->ItemIcon (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (3)->ItemIcon (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (4)->ItemIcon (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (5)->ItemIcon (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (6)->ItemIcon (6) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (6) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (7)->ItemIcon (7) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (7) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (8)->ItemIcon (8) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->ItemSlot (8) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_0 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_1 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_2 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_3 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_4 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_5 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_6 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase->ItemSlider_7 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask->ItemSlideAnimationBase (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Mask (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_0 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_1 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_2 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_3 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_4 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_5 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_6 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_7 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers->ItemCover_8 (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots->Covers (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemSlots (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->JohnnyBase (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->JohnnyMouth (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemDescription (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Total (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (6) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Amount (7) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemImages->Image (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemImages->Image (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemImages->Image (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemImages->Image (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemImages->Image (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemImages->Image (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ItemImages (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BoughtImages->Image (0) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BoughtImages->Image (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BoughtImages->Image (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BoughtImages->Image (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BoughtImages->Image (4) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BoughtImages->Image (5) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->BoughtImages (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Back (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->DraggableAnchor->Draggable (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->DraggableAnchor (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->ChalkBoard (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->Text (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->YesButton->Yes (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->YesButton->Yes_Lit (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->YesButton (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->NoButton->Yes (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->NoButton->Yes_Lit (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm->NoButton (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->ExitConfirm (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Bottom->Border (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Bottom->Border (1) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Bottom->Border (2) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Bottom->Border (3) (RectTransform)
	ElevatorScreen->StoreScreen->Canvas->Bottom (RectTransform)
	ElevatorScreen->StoreScreen->Canvas (RectTransform)
	Alarm Clock->RendererBase->Sprite (SpriteRenderer)
	GrapplingHook->RendererBase->Sprite (SpriteRenderer)
	NanaPeel->RendererBase->Sprite (SpriteRenderer)
	GrapplingHook1->RendererBase->Sprite (SpriteRenderer)
	GrapplingHook2->RendererBase->Sprite (SpriteRenderer)
	GrapplingHook3->RendererBase->Sprite (SpriteRenderer)
	GrapplingHook4->RendererBase->Sprite (SpriteRenderer)
	CoreGameManager->PauseMenuScreens->PauseScreen->BG (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (1) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (2) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (3) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (4) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (5) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (6) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (7) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (8) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (9) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (10) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (11) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (12) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (13) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (14) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (15) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (16) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (17) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (18) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (19) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (23) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (20) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (21) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Image (24) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG->Dummy (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->BaldiBG (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Main->SeedLabel (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Main->SeedTMP (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Main->PauseLabel (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Main->ResumeButton (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Main->OptionsButton (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Main->QuitButton (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Main (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->QuitConfirm->Text (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->QuitConfirm->YesButton (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->QuitConfirm->NoButton (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->QuitConfirm (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Bottom->Border (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Bottom->Border (1) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Bottom->Border (2) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Bottom->Border (3) (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen->Bottom (RectTransform)
	CoreGameManager->PauseMenuScreens->PauseScreen (RectTransform)
