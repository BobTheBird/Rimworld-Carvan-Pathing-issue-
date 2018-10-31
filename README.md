# Rimworld-Carvan-Pathing-issue-
Caravans will not leave home and will wonder in circles instead

Log uploaded on Wednesday, October 31, 2018, 2:31:27 PM
Loaded mods:
Core: (no assemblies)
HugsLib[6.0.1]: 0Harmony(1.2.0.1), HugsLib(1.0.0.0)
Better Pawn Control[1.9.3]: $HugsLibChecker(0.5.0.0), BetterPawnControl(1.9.2.0)
More Faction Interaction: 0Harmony(1.2.0.1), MoreFactionInteraction(0.1.0.8)
Alpha Animals: 0Harmony(1.2.0.1), AlphaAnimalRangeUnlocker(1.0.6862.18063), AlphaBehavioursAndEvents(1.0.0.0), AnimalVariations(1.0.6818.33624), ModCheck(1.8.0.0), NewAlphaAnimalSubproducts(1.0.0.0)
Realistic Human Sounds: (no assemblies)
[XND] Turret Extensions: 0Harmony(1.2.0.1), TurretExtensions(1.2.4.0)
[XND] TE Turret Expansion: (no assemblies)
Weapon Tech: WeaponTech(1.0.0.0)
Frontline - Bunkers: (no assemblies)
Color Coded Mood Bar: 0Harmony(1.2.0.1), ColoredMoodBar(1.0.0.0)
[T] MoreFloors: (no assemblies)

Active Harmony patches:
<GizmoOnGUI>c__AnonStorey0.<>m__0: TRANS: TurretExtensions.HarmonyPatches.TranspileGizmoOnGUIDelegate
Building_TurretGun.BurstCooldownTime: post: TurretExtensions.HarmonyPatches.PostfixBurstCooldownTime
Building_TurretGun.GetInspectString: TRANS: TurretExtensions.HarmonyPatches.TranspileGetInspectString
Building_TurretGun.SpawnSetup: post: TurretExtensions.HarmonyPatches.PostfixSpawnSetup
Building_TurretGun.Tick: PRE: TurretExtensions.HarmonyPatches.PrefixTick
Building_TurretGun.TryStartShootSomething: post: TurretExtensions.HarmonyPatches.PostfixTryStartShootSomething
Building_TurretGun.get_CanSetForcedTarget: post: TurretExtensions.HarmonyPatches.PostfixCanSetForcedTarget
ColonistBarColonistDrawer.DrawColonist: PRE: MoodBarPatch.MoodPatch.Prefix
CompPowerTrader.SetUpPowerVars: post: TurretExtensions.HarmonyPatches.PostfixSetUpPowerVars
CompQuality.PostPostGeneratedForTrader: PRE: MoreFactionInteraction.HarmonyPatches.CompQuality_TradeQualityIncreasePreFix
CompRefuelable.CompInspectStringExtra: TRANS: TurretExtensions.HarmonyPatches.CompRefuelable_FuelCapacityTranspiler
CompRefuelable.GetFuelCountToFullyRefuel: TRANS: TurretExtensions.HarmonyPatches.TranspileGetFuelCountToFullyRefuel
CompRefuelable.Refuel: TRANS: TurretExtensions.HarmonyPatches.CompRefuelable_FuelCapacityTranspiler
CompRefuelable.get_TargetFuelLevel: TRANS: TurretExtensions.HarmonyPatches.CompRefuelable_FuelCapacityTranspiler
CompRefuelable.set_TargetFuelLevel: TRANS: TurretExtensions.HarmonyPatches.CompRefuelable_FuelCapacityTranspiler
DebugWindowsOpener.DevToolStarterOnGUI: TRANS: HugsLib.Patches.DevToolStarterOnGUI_Patch.ExtendButtonsWindow
DebugWindowsOpener.DrawButtons: TRANS: HugsLib.Patches.DebugWindowsOpener_Patch.DrawAdditionalButtons
DebugWindowsOpener.ToggleDebugActionsMenu: TRANS: MoreFactionInteraction.HarmonyPatches.DebugWindowsOpener_ToggleDebugActionsMenu_Patch
Designator_Cancel.DesignateThing: PRE: TurretExtensions.HarmonyPatches.PrefixDesignateThing
Dialog_Options.DoWindowContents: TRANS: HugsLib.Patches.Dialog_Options_Patch.ReplaceModOptionsButton
EditWindow_Log.DoMessagesListing: PRE: HugsLib.Patches.EditWindow_Log_Patch.ExtraLogWindowButtons
Game.DeinitAndRemoveMap: post: HugsLib.Patches.Game_DeinitAndRemoveMap_Patch.MapRemovalHook
Game.FillComponents: PRE: HugsLib.Patches.Game_FillComponents_Patch.GameInitializationHook
Game.FinalizeInit: post: HugsLib.Patches.Game_FinalizeInit_Patch.WorldLoadedHook
JobGiver_AIDefendPawn.TryGiveJob: PRE: AlphaAnimalRangeAttack.ARA_FightAI_Patch.Prefix
JobGiver_Manhunter.TryGiveJob: PRE: AlphaAnimalRangeAttack.ARA__ManHunter_Patch.Prefix
LanguageDatabase.SelectLanguage: PRE: HugsLib.Patches.LanguageDatabase_Patch.ForceRestartAfterLangChange
LoadedModManager.ApplyPatches: PRE: ModCheck.VanillaPatching.Prefix post: ModCheck.VanillaPatching.Postfix TRANS: ModCheck.VanillaPatching.Transpiler
MainMenuDrawer.MainMenuOnGUI: post: ModCheck.DoneLoading.Postfix
Map.ConstructComponents: post: HugsLib.Patches.Map_ConstructComponents_Patch.MapComponentsInitHook
Map.FinalizeInit: post: HugsLib.Patches.Map_FinalizeInit_Patch.MapLoadedHook
MapComponentUtility.MapGenerated: post: HugsLib.Patches.MapComponentUtility_MapGenerated_Patch.MapGeneratedHook
ModsConfig.RestartFromChangedMods: PRE: HugsLib.Patches.ModsConfig_RestartFromChangedMods_Patch.QuickRestartInDevMode
Pawn.TryGetAttackVerb: PRE: AlphaAnimalRangeAttack.ARA__VerbCheck_Patch.Prefix
PlayDataLoader.DoPlayLoad: post: HugsLib.Patches.PlayDataLoader_Patch.InitModsHook
ReverseDesignatorDatabase.InitDesignators: post: TurretExtensions.HarmonyPatches.PostfixInitDesignators
Root.Update: post: HugsLib.Patches.Root_Patch.UpdateHook
Root_Play.SetupForQuickTestPlay: TRANS: HugsLib.Patches.RootPlay_TestPlay_Patch.InjectCustomQuickstartSettings
SettlementBase.GetCaravanGizmos: post: MoreFactionInteraction.HarmonyPatches.SettlementBase_CaravanGizmos_Postfix
StatWorker.GetExplanationUnfinalized: post: TurretExtensions.HarmonyPatches.PostfixGetExplanationUnfinalized
StatWorker.GetValueUnfinalized: post: TurretExtensions.HarmonyPatches.PostfixGetValueUnfinalized
StatsReportUtility.DescriptionEntry: post: TurretExtensions.HarmonyPatches.PostfixDescriptionEntry
StatsReportUtility.StatsToDraw: post: TurretExtensions.HarmonyPatches.PostfixStatsToDraw_ThingDef
StatsReportUtility.StatsToDraw: post: TurretExtensions.HarmonyPatches.PostfixStatsToDraw_Thing
StoryState.Notify_IncidentFired: post: MoreFactionInteraction.HarmonyPatches.IncidentFired_TradeCounter_Postfix
Thing.ButcherProducts: post: NewAlphaAnimalSubproducts.Thing_ButcherProducts_Patch.ChangeMeatAmountByAge
Thing.get_Graphic: post: TurretExtensions.HarmonyPatches.PostfixGraphic
ThingDef.SpecialDisplayStats: post: TurretExtensions.HarmonyPatches.ThingDef_PostfixSpecialDisplayStats
ThingSetMaker.Generate: post: MoreFactionInteraction.HarmonyPatches.TraderStocker_OverStockerPostFix
Tradeable.InitPriceDataIfNeeded: TRANS: MoreFactionInteraction.HarmonyPatches.ErrorSuppressionSssh
TraderKindDef.PriceTypeFor: post: MoreFactionInteraction.HarmonyPatches.PriceTypeSetter_PostFix
TurretTop.DrawTurret: TRANS: TurretExtensions.HarmonyPatches.TranspileDrawTurret
UIRoot.UIRootOnGUI: post: HugsLib.Patches.UIRoot_Patch.OnGUIHook
WorldReachabilityUtility.CanReach: post: MoreFactionInteraction.HarmonyPatches.WorldReachUtility_PostFix
Harmony versions present: 1.2.0.1: UnlimitedHugs.HugsLib, com.rimworld.modcheck, Mehni.RimWorld.MFI.main, com.github.rimworld.mod.AlphaAnimalRangeAttack, com.alphaanimals, XeoNovaDan.TurretExtensions, com.github.restive2k12.rimworld.mod.moodbar

Platform information: (hidden, hold Shift while publishing to include)

Log file contents:
Initialize engine version: 5.6.5f1 (2cac56bf7bb6)
GfxDevice: [Renderer information redacted]
Begin MonoManager ReloadAssembly
Loading [Rimworld_dir]/Contents/Resources/Data/Managed/UnityEngine.dll into Unity Child Domain
Loading [Rimworld_dir]/Contents/Resources/Data/Managed/Assembly-CSharp-firstpass.dll into Unity Child Domain
Loading [Rimworld_dir]/Contents/Resources/Data/Managed/Assembly-CSharp.dll into Unity Child Domain
Loading [Rimworld_dir]/Contents/Resources/Data/Managed/UnityEngine.UI.dll into Unity Child Domain
Loading [Rimworld_dir]/Contents/Resources/Data/Managed/UnityEngine.Networking.dll into Unity Child Domain
Loading [Rimworld_dir]/Contents/Resources/Data/Managed/TextMeshPro-1.0.55.56.0b11.dll into Unity Child Domain
Setting breakpad minidump AppID = 294100
[Steam Id redacted]
RimWorld 1.0.2059 rev1006
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

Turret Extensions successfully completed 23 patches with harmony.
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

[ColorCodedMoodBar] initialized
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

[HugsLib] v6.0.1 initialized BetterPawnControl
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

Unloading 5 Unused Serialized files (Serialized files now loaded: 0)

Unloading 41 unused Assets to reduce memory usage. Loaded Objects now: 9765.
Total: 33.766491 ms (FindLiveObjects: 0.476890 ms CreateObjectMapping: 0.563142 ms MarkObjects: 32.669189 ms  DeleteObjects: 0.056337 ms)

Loading game from file Autosave-5 with mods Core, 818773962, 1541460369, 1454024362, 1541721856, 1543157058, 1496122245, 1496140597, 1542854752, 1545794905, 1501832876, 1543561093
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

Could not do PostLoadInit on Verse.AI.Group.Lord: System.NullReferenceException: Object reference not set to an instance of an object
  at RimWorld.LordJob_AssaultColony.CreateGraph () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.Lord.SetJob (Verse.AI.Group.LordJob lordJob) [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.Lord.ExposeData_StateGraph () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.Lord.ExposeData () [0x00000] in <filename unknown>:0 
  at Verse.PostLoadIniter.DoAllPostLoadInits () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

Unloading 0 Unused Serialized files (Serialized files now loaded: 0)

Unloading 0 unused Assets to reduce memory usage. Loaded Objects now: 16100.
Total: 132.694839 ms (FindLiveObjects: 1.034063 ms CreateObjectMapping: 1.149363 ms MarkObjects: 130.479736 ms  DeleteObjects: 0.031216 ms)

Random state stack is not empty. There were more calls to PushState than PopState. Fixing.
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

System.NullReferenceException: Object reference not set to an instance of an object
  at Verse.AI.Group.Lord.LordTick () [0x00000] in <filename unknown>:0 
  at Verse.AI.Group.LordManager.LordManagerTick () [0x00000] in <filename unknown>:0 
  at Verse.Map.MapPostTick () [0x00000] in <filename unknown>:0 
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)

Reached max messages limit. Stopping logging to avoid spam.
(Filename: /Users/builduser/buildslave/unity/build/artifacts/generated/common/runtime/DebugBindings.gen.cpp Line: 51)
