[Message:   BepInEx] BepInEx 5.4.21.0 - Content Warning (9/23/2024 3:11:58 PM)
[Info   :   BepInEx] Running under Unity v2022.3.10.16725906
[Info   :   BepInEx] CLR runtime version: 4.0.30319.42000
[Info   :   BepInEx] Supports SRE: True
[Info   :   BepInEx] System platform: Bits64, Windows
[Message:   BepInEx] Preloader started
[Info   :   BepInEx] Loaded 1 patcher method from [BepInEx.Preloader 5.4.21.0]
[Info   :   BepInEx] 1 patcher plugin loaded
[Info   :   BepInEx] Patching [UnityEngine.CoreModule] with [BepInEx.Chainloader]
[Message:   BepInEx] Preloader finished
[Message:   BepInEx] Chainloader ready
[Message:   BepInEx] Chainloader started
[Info   :   BepInEx] 2 plugins to load
[Info   :   BepInEx] Loading [Mycelium Networking 1.0.14]
[Info   :RugbugRedfern.MyceliumNetworking] MyceliumNetworking Starting 1.0.14
[Info   :   BepInEx] Loading [Found Footage 0.4.4]
[Info   :Found Footage] Generated user UUID: c9407557-1240-48d5-b3eb-d3c4b63f295f
[Info   :Found Footage] Generated secret user UUID: ************************************
[Info   :Found Footage] Plugin jp.assasans.cw.FoundFootage is loaded!
[Info   :Found Footage] Plugin jp.assasans.cw.FoundFootage patched!
[Info   :Found Footage] Server URL: https://foundfootage-server.assasans.dev
[Info   :RugbugRedfern.MyceliumNetworking] Registered 1 CustomRPCs for 551035154: BepInEx_Manager (FoundFootage.FoundFootagePlugin).
[Info   :Found Footage] Migrated to config version 2
[Message:   BepInEx] Chainloader startup complete
[Info   : Unity Log] Odin Serializer ArchitectureInfo initialization with defaults (all unaligned read/writes disabled).
[Info   : Unity Log] Odin Serializer detected whitelisted runtime platform WindowsPlayer and memory read test succeeded; enabling all unaligned memory read/writes.
[Info   :Found Footage] Trace: {"secretUserId":"369301f4-d48b-4130-8f91-1fec56633a33","values":"SpawnChance=0.3\nDeathUploadChance=1\nPassUploadChance=0.25\nDeathVideoChance=0.75\nVotingEnabled=True\nSendPositionEnabled=True\nSendContentBufferEnabled=True\nFoundVideoScoreMultiplier=0.5\nFoundVideoSearchParams=[LANGUAGE, DAY]"}
[Info   : Unity Log] Cmd argument: C:\Program Files (x86)\Steam\steamapps\common\Content Warning\Content Warning.exe
[Info   : Unity Log] Cmd argument: --doorstop-enable
[Info   : Unity Log] Cmd argument: true
[Info   : Unity Log] Cmd argument: --doorstop-target
[Info   : Unity Log] Cmd argument: C:\Users\Windows\AppData\Roaming\r2modmanPlus-local\ContentWarning\profiles\test\BepInEx\core\BepInEx.Preloader.dll
[Info   : Unity Log] Switched State to: NoneState
[Info   : Unity Log] Entered None State
[Info   : Unity Log] Time of day set to Morning
[Info   : Unity Log] Loading saves...
[Info   : Unity Log] SaveSystem Init, Save Location: C:/Users/Windows/AppData/LocalLow/Landfall Games/Content Warning/Saves/
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Error  : Unity Log] NullReferenceException: Object reference not set to an instance of an object
Stack trace:
SettingsMenu.Show (SettingCategory category) (at <947345cdc4fa4847a35c09349dc3a8e0>:0)
SettingsMenu.SelectCategory (SettingCategory settingCategory) (at <947345cdc4fa4847a35c09349dc3a8e0>:0)
SettingCategoryTab.Select () (at <947345cdc4fa4847a35c09349dc3a8e0>:0)
Zorro.UI.TAB_Button.Select () (at <b7a6a1f1507542dfac6b3aad805d5639>:0)
Zorro.UI.TABS`1[ButtonType].Select (ButtonType button) (at <b7a6a1f1507542dfac6b3aad805d5639>:0)
SettingsMenu.OnEnable () (at <947345cdc4fa4847a35c09349dc3a8e0>:0)

[Warning: Unity Log] Failed to load setting of type EdgeDetectionSetting from PlayerPrefs.
[Warning: Unity Log] Failed to load setting of type WorldShaderSetting from PlayerPrefs.
[Info   : Unity Log] WorldShaderSetting ApplyValue() called. Value: 0
[Warning: Unity Log] Failed to load setting of type VoiceSetting from PlayerPrefs. Value not found in choices.
[Info   : Unity Log] Voice setting applied: Microphone (AQIRYS Altair 7.1 Headset)
[Info   : Unity Log] noext: AZorros_Adventure_Rarity100Score663
[Info   : Unity Log] Name: AZorros Adventure Rarity100
[Info   : Unity Log] noext: Petter_StoryRarity200Score334
[Info   : Unity Log] Name: Petter Story Rarity200
[Info   : Unity Log] noext: Wilhelm_PoopsRarity010Score555
[Info   : Unity Log] Name: Wilhelm Poops Rarity10
[Info   : Unity Log] Failed to initialize Discord Rich Presence: Discord.ResultException: InternalError
  at Discord.Discord..ctor (System.Int64 clientId, System.UInt64 flags) [0x00327] in <56b8d6adf1cd4fcda992a5495e5b1dd7>:0 
  at RichPresenceHandler.Initialize () [0x00000] in <947345cdc4fa4847a35c09349dc3a8e0>:0 
[Info   : Unity Log] MetaProgressionHandler initialized
[Info   : Unity Log] Meta progression data loaded
[Info   : Unity Log] Deleting MetaFile!
[Warning: Unity Log] Found plugin with no attribute. Will be treated as non-compatible with vanilla: C:\Users\Windows\AppData\Roaming\r2modmanPlus-local\ContentWarning\profiles\test\BepInEx\plugins\RugbugRedfern-MyceliumNetworking\MyceliumNetworking\MyceliumNetworkingForCW.dll
[Info   : Unity Log] Found plugin with Attribute: jp.assasans.cw.FoundFootage.dll, guid: jp.assasans.cw.FoundFootage, version:  0.4.4, VanillaCompatible: False
[Info   : Unity Log] Plugin hash: be978d93c0cfc5e17573020de65fec90
[Info   : Unity Log] Initialized Type Parser for Item
[Info   : Unity Log] Initialized Type Parser for NetworkDealBase
[Info   : Unity Log] Initialized Type Parser for System.Single
[Info   : Unity Log] Initialized Type Parser for System.Int32
[Info   :Found Footage] Local version 0.4.4 is compatible with remote 0.4.4 (0.4.3-compatible; 0.4.2-compatible; 0.4.1-compatible; 0.4.0-compatible; 0.3.1-compatible; 0.3.0-compatible; 0.2.2-compatible; 0.2.1-compatible; 0.2.0-compatible; 0.1.0-compatible)
[Info   : Unity Log] MainMenuHandler Start
[Info   : Unity Log] Photon State: PeerCreated
[Info   : Unity Log] Photon StartConnectingToNameServer using app version: 1.18
[Info   : Unity Log] SteamLobbyHandler Started With Max Players: 4
[Error  : Unity Log] Leave SteamLobby Called but Cant Leave Since No Active Lobby!
[Info   :RugbugRedfern.MyceliumNetworking] Patching SteamLobbyHandler.LeaveLobby
[Info   : Unity Log] Deleting Folder: C:\Users\Windows\AppData\Local\Temp\rec
[Info   : Unity Log] Switched State to: MatchmakingIdleState
[Info   : Unity Log] Startup Steam Language: english
[Info   : Unity Log] Changed Unity Language to: English (en)
[Info   : Unity Log] Registering page: Settings
[Info   : Unity Log] Registering page: Videos
[Info   : Unity Log] Registering page: Game State
[Info   : Unity Log] Registering page: Network Deals
[Info   : Unity Log] Registering page: Save/Load
[Info   : Unity Log] Transitioning to LoadingPage
[Info   : Unity Log] Connected to Photon Master Server: eu
[Info   : Unity Log] Steam CMD Line 
[Info   : Unity Log] Transitioning to MainPage
[Info   : Unity Log] Transitioning to HostPage
[Info   : Unity Log] Transitioning to LoadingPage
[Error  : Unity Log] Cant Save Outside Of Room
[Info   : Unity Log] Steam Lobby Created Callback k_EResultOK BioFail False
[Info   : Unity Log] Making lobby not joinable to wait for photon
[Info   : Unity Log] Set Lobby Language: 9
[Info   : Unity Log] Steam Lobby Hosted: 109775240922344471 Hosting PhotonRoom Now
[Info   : Unity Log] Created Photon Room... 
[Info   : Unity Log] Creating new save with index: 1
[Info   : Unity Log] Making New Save for index1 
[Info   :RugbugRedfern.MyceliumNetworking] Created lobby k_EResultOK
[Info   :RugbugRedfern.MyceliumNetworking] Entering lobby 109775240922344471
[Info   : Unity Log] Hosted Photon Room: 2bcb2733-39b5-48ee-a478-71e5206f2622 Cluster: 87.120.167.6:5056
[Info   : Unity Log] Setting SteamLobby Region Data: eu
[Info   : Unity Log] Set Lobby Language: English, success: True
[Info   : Unity Log] Exited None State
[Info   : Unity Log] Switched State to: InRoomState
[Info   : Unity Log] Registering package with event code 1 and type StartRecordingCommandPackage
[Info   : Unity Log] Registering package with event code 2 and type StopRecordingCommandPackage
[Info   : Unity Log] Registering package with event code 51 and type SendVideoChunkPackage
[Info   : Unity Log] Registering package with event code 50 and type AddClipToShareQueuePackage
[Info   : Unity Log] Registering package with event code 52 and type ActivateNextSharingJobPackage
[Info   : Unity Log] Registering package with event code 53 and type SendClipCompletedPackage
[Info   : Unity Log] Registering package with event code 30 and type ItemInstancePackage
[Info   : Unity Log] Registering package with event code 54 and type ReRequestClipPackage
[Info   : Unity Log] Registering package with event code 21 and type KickPlayerNotificationPackage
[Info   : Unity Log] INIT PhotonSendVideoHandler with path: C:\Users\Windows\AppData\Local\Temp\rec Exist? False
[Info   : Unity Log] Loading Game Scene: SurfaceScene
[Info   : Unity Log] Photon is loading level: SurfaceScene
[Info   : Unity Log] Listener added: ExtractVideoMachine
[Info   : Unity Log] Time of day changed to Morning
[Info   : Unity Log] Switched State to: ExtractMachineClosedState
[Info   : Unity Log] SurfaceNetworkHandler Awake! InRoom : True
[Info   : Unity Log] Listener added: ShopViewScreen
[Warning: Unity Log] Cant find locKey for: Hat_HardHat
[Info   : Unity Log] Listener added: UploadVideoStation
[Error  :Found Footage] Root: UploadMachine2 (UnityEngine.GameObject)
[Error  :Found Footage] SaveVideo: SaveVideo (UnityEngine.GameObject)
[Error  :Found Footage] ReplayInt: ReplayInt (UnityEngine.GameObject)
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] [2024-09-23T12:43:22] [INFO] [INIT] [] An instance of PunVoiceClient is found in the scene.
[Info   : Unity Log] [2024-09-23T12:43:22] [INFO] [INIT] [] PunVoiceClient singleton instance is now set.
[Warning: Unity Log] [2024-09-23T12:43:22] [WARNING] [INIT] [] VoiceLogger object is not found in the scene. Creating one.
[Info   : Unity Log] Listener handle for type ItemInstancePackage already exists, removing old handles
[Info   : Unity Log] Listener added: EveningToggler
[Info   : Unity Log] Time of day changed to Morning
[Info   : Unity Log] Switched State to: UploadVideoClosedState
[Info   : Unity Log] Initializing Surface
[Info   : Unity Log] Setting Quota to reach To: 300 From: 0
[Info   : Unity Log] Setting Quota To: 0 From: 0
[Info   : Unity Log] Master Regen ew Seed: 1405320908
[Info   : Unity Log] NEW DAY: 1 Current QuotaDay: 1Days Left To Complete Quota Of: 300 : 2
[Info   : Unity Log] Showing Helmet Text: Day 1 for 3 seconds
[Info   : Unity Log] NEW RUN!
[Warning: Unity Log] Couldn't create a Convex Mesh from source mesh "Cube" within the maximum polygons limit (256). The partial hull will be used. Consider simplifying your mesh.
[Warning: Unity Log] Couldn't create a Convex Mesh from source mesh "Cube" within the maximum polygons limit (256). The partial hull will be used. Consider simplifying your mesh.
[Warning: Unity Log] Couldn't create a Convex Mesh from source mesh "Cylinder" within the maximum polygons limit (256). The partial hull will be used. Consider simplifying your mesh.
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 00000000-0000-0000-0000-000000000000
[Info   : Unity Log] Spawning local player: House
[Info   : Unity Log] Shop Started, Initializing...
[Error  : Unity Log] Failed to get Localized displayName for: Sketch Pad
[Info   : Unity Log] GameLobby Started, Surface: True
[Warning: Unity Log] OnPlayerJoined
[Warning: Unity Log] Player(Clone) is sleeping in bed 0
[Error  : Unity Log] all beds are full
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] Switched State to: DivingBellNotReadyMissingPlayersState
[Warning: Unity Log] [2024-09-23T12:43:23] [WARNING] [Recorder] [Voice] [PV] MicWrapper: microphone does not support suggested frequency 24000 (min: 48000, max: 48000). Setting to 48000
[Warning: Unity Log] [2024-09-23T12:43:23] [WARNING] [PunVoiceClient] [VoiceClient] [PV] Local voice #1 audio source frequency 48000 and encoder sampling rate 24000 do not match. Resampling will occur before encoding (FramerResampler, interp).
[Info   : Unity Log] visor setting text to: >;3
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] Setting microphone to Microphone (AQIRYS Altair 7.1 Headset)
[Warning: Unity Log] [2024-09-23T12:43:23] [WARNING] [Recorder] [Voice] [PV] MicWrapper: microphone does not support suggested frequency 24000 (min: 48000, max: 48000). Setting to 48000
[Warning: Unity Log] [2024-09-23T12:43:23] [WARNING] [PunVoiceClient] [VoiceClient] [PV] Local voice #2 audio source frequency 48000 and encoder sampling rate 24000 do not match. Resampling will occur before encoding (FramerResampler, interp).
[Info   : Unity Log] Calling OpJoinOrCreateRoom for room name '2bcb2733-39b5-48ee-a478-71e5206f2622_voice_' region eu.
[Info   : Unity Log] Changing Voice Channels Should Talk to and Hear Everyone!
[Info   :Found Footage] Found dislike sprite: Skull-1--Streamline-Ultimate (1) (UnityEngine.Sprite)
[Info   :Found Footage] Found like sprite: Emoji-Great--Streamline-Ultimate (UnityEngine.Sprite)
[Info   : Unity Log] Showing modal with title: Are you sure you want to start?
[Info   : Unity Log] Starting Game, Locking In Players
1 Playerscrisaliv

[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 00000000-0000-0000-0000-000000000000
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellReadyState
[Info   : Unity Log] Day 1 Going To FactoryScene
[Info   : Unity Log] Looking for Surface persistant objects...
[Info   : Unity Log] Photon is loading level: FactoryScene
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Warning: Unity Log] Cant find locKey for: Hat_HardHat
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Time of day set to Evening
[Info   : Unity Log] Persistant Objects, Not Same Scene, Not Spawning
[Info   : Unity Log] Listener handle for type ItemInstancePackage already exists, removing old handles
[Info   : Unity Log] Spawning local player: DiveBell
[Info   : Unity Log] [2024-09-23T12:43:47] [INFO] [LOGGER] [VoiceLogger] Disabling VoiceLogger duplicates at the scene root.
[Info   : Unity Log] Start Artifact round spawner
[Info   : Unity Log] Start Artifact round spawner
[Info   : Unity Log] GameLobby Started, Surface: False
[Info   : Unity Log] Switched State to: DivingBellReadyState
[Warning: Unity Log] [2024-09-23T12:43:47] [WARNING] [Recorder] [Voice] [PV] MicWrapper: microphone does not support suggested frequency 24000 (min: 48000, max: 48000). Setting to 48000
[Warning: Unity Log] [2024-09-23T12:43:47] [WARNING] [PunVoiceClient] [VoiceClient] [PV] Local voice #3 audio source frequency 48000 and encoder sampling rate 24000 do not match. Resampling will occur before encoding (FramerResampler, interp).
[Info   : Unity Log] visor setting text to: >;3
[Info   : Unity Log] Setting microphone to Microphone (AQIRYS Altair 7.1 Headset)
[Warning: Unity Log] 1st wave Day: 1 quotaDay: 1 budget 7
[Warning: Unity Log] 2nd wave Day: 1 quotaDay: 1 budget 13
[Info   : Unity Log] MB FOR DAY 1: Budget: 7, 2nd: 13, BiggestPurchase: 5 WaitTime 265.6037
[Info   : Unity Log] spawned 4 monsters
[Info   : Unity Log] Spawning 5 late monsters, all before 265.6037
[Info   : Unity Log] will spawn Weeping after 21.99405 seconds
[Info   : Unity Log] will spawn Slurper after 132.272 seconds
[Info   : Unity Log] will spawn Zombe after 142.5723 seconds
[Info   : Unity Log] will spawn Ear after 212.9018 seconds
[Info   : Unity Log] will spawn Puffo after 113.6307 seconds
[Info   : Unity Log] ToolSpawner Day1 Budget: 3, BiggestPurchase: 0
[Info   : Unity Log] MB FOR DAY 1: Budget: 10, BiggestPurchase: 0
[Info   :Found Footage] Start shitted
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-0d58-498a-ab17-f9105114c1b4
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-0d58-498a-ab17-f9105114c1b4
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (-25.13, -19.70, -32.02)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-5aab-49f6-a1f4-43d8642df737
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-5aab-49f6-a1f4-43d8642df737
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (-30.34, -20.21, -90.63)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-691c-4bfc-9f8b-184c934b7a5c
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-691c-4bfc-9f8b-184c934b7a5c
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (-30.15, -19.70, 6.14)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-3973-457c-be8d-9d7b933fbcd9
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-3973-457c-be8d-9d7b933fbcd9
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (-67.53, -20.21, -140.87)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (4.04, -16.41, -143.24)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-e7da-4e43-82b8-f1630f8805f8
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-e7da-4e43-82b8-f1630f8805f8
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (-35.47, -19.70, -6.96)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-d6e0-4667-91f2-792951f12ccc
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-d6e0-4667-91f2-792951f12ccc
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (-12.51, -19.70, 13.98)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawning found camera!
[Info   :Found Footage] [RoundArtifactSpawnerPatch] added entry 7fffffff-756a-4fd4-ab06-1dfb485f3d0d
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-756a-4fd4-ab06-1dfb485f3d0d
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] [RoundArtifactSpawnerPatch] Spawned found camera at (-51.83, -19.70, -8.82)!
[Info   :Found Footage] Start shitted
[Info   :Found Footage] Start shitted
[Info   :Found Footage] Start shitted
[Warning: Unity Log] [2024-09-23T12:43:47] [WARNING] [Recorder] [Voice] [PV] MicWrapper: microphone does not support suggested frequency 24000 (min: 48000, max: 48000). Setting to 48000
[Warning: Unity Log] [2024-09-23T12:43:47] [WARNING] [PunVoiceClient] [VoiceClient] [PV] Local voice #4 audio source frequency 48000 and encoder sampling rate 24000 do not match. Resampling will occur before encoding (FramerResampler, interp).
[Info   : Unity Log] Battery entry not found, adding new entry with full charge.
[Info   : Unity Log] OnOff entry not found, adding new entry with false.
[Info   : Unity Log] Registering RPC RPC0 for item 17cbc9cf-25c8-478b-a3c7-84c1119d0bb3 with action RPC_Shock
[Info   : Unity Log] OnOff entry not found, adding new entry with false.
[Info   : Unity Log] Battery entry not found, adding new entry with full charge.
[Info   : Unity Log] OnOff entry not found, adding new entry with false.
[Info   : Unity Log] Registering RPC RPC0 for item 575fa742-efe4-4426-a321-57ba34cf8832 with action RPC_Shock
[Error  : Unity Log] Failed to get Localized displayName for: Shroom
[Info   : Unity Log] stashAbleEntry entry not found, adding new entry with true.
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 00000000-0000-0000-0000-000000000000
[Info   : Unity Log] Spawning Weeping after 21.99405 seconds
[Warning: Unity Log] Couldn't create a Convex Mesh from source mesh "Sphere" within the maximum polygons limit (256). The partial hull will be used. Consider simplifying your mesh.
[Info   : Unity Log] spawned Weeping in Delayed Wave
[Error  : Unity Log] Monster PLAYER is NULL at Weeping(Clone)
[Warning: Unity Log] BoxColliders does not support negative scale or size.
The effective box size has been forced positive and is likely to give unexpected collision geometry.
If you absolutely need to use negative scaling you can use the convex MeshCollider. Scene hierarchy path "Weeping(Clone)/CaptchaCage/CaptchaCage/Arm (2)/Elbow/Hand/Bone/Phone/Cube"
[Info   : Unity Log] spawned 1 monsters
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] Check ProcessedFakeVideos
[Info   :Found Footage] CreateFakeVideo start
[Info   :Found Footage] FoundVideoSearchParamsParsed: LANGUAGE, DAY
[Error  : Unity Log] ArgumentException: JSON parse error: Invalid value.
Stack trace:
UnityEngine.JsonUtility.FromJson (System.String json, System.Type type) (at <890bfa9eb11c4f359e8d674787b8d446>:0)
UnityEngine.JsonUtility.FromJson[T] (System.String json) (at <890bfa9eb11c4f359e8d674787b8d446>:0)
FoundFootage.Patches.VideoCameraPatch+<DownloadFakeVideoSignedUrl_Unity>d__2.MoveNext () (at <0d3e4ed898fe4b09a38e4c2dad691a71>:0)
UnityEngine.SetupCoroutine.InvokeMoveNext (System.Collections.IEnumerator enumerator, System.IntPtr returnValueAddress) (at <801ef9485ea54ad392ab1752511dc748>:0)

[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 00000000-0000-0000-0000-000000000000
[Info   : Unity Log] Camera has no video ID, creating new video ID, 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   : Unity Log] Creating new recording: 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   : Unity Log] video 5d8c72ca added new clip: 9235507b, total clips: 1
[Info   : Unity Log] Start recording, camera instance id:867c23e6-3331-459f-9502-7d2676042661, video ID: 5d8c72ca-d2a6-4e8e-8786-ac22706bee63, clip ID: 9235507b-2186-422b-8e39-9408a8905e1c
[Info   : Unity Log] Setting camera to send audio to Clip Recorder: 923
[Info   : Unity Log] Setting sample rate to: 48000
[Info   : Unity Log] Setting channels to 1
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.025 on frame: 8969
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0275 on frame: 8978
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.03 on frame: 8987
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.02 on frame: 8996
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.02 on frame: 9005
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.025 on frame: 9014
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.03 on frame: 9023
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.02 on frame: 9032
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.02 on frame: 9041
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0225 on frame: 9050
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0175 on frame: 9059
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0175 on frame: 9068
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.02 on frame: 9077
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0175 on frame: 9086
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0175 on frame: 9095
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0175 on frame: 9104
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.015 on frame: 9113
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9122
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.015 on frame: 9131
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9140
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9149
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0175 on frame: 9158
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.015 on frame: 9167
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9176
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9185
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9194
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9203
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9212
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9221
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9239
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9248
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0125 on frame: 9257
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9266
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9275
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9284
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9293
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9302
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9311
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9320
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9329
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9338
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9347
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9356
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9365
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9374
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9383
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9392
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9401
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9410
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9419
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9428
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9437
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9446
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9455
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9464
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9473
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9482
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9482
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9492
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9492
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9501
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9501
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9510
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9510
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9519
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9519
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9525
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9525
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9534
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9534
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.005 on frame: 9543
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9543
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0075 on frame: 9552
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9561
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9561
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9570
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9579
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9588
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9588
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9597
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9606
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9606
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9615
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9624
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9633
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.01 on frame: 9642
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9651
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9660
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9660
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9669
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9678
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9687
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9696
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9705
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9714
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9723
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9723
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9732
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9741
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9750
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9759
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9768
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9768
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9777
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9786
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9795
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9804
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9813
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9822
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9822
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9831
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9840
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9846
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9855
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 9864
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9864
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9873
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9882
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 9891
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9900
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9909
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9918
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9927
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9936
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9945
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9954
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9963
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9972
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9981
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 9990
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10000
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10009
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10018
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10027
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 10036
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10036
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10045
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10054
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10072
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10081
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10090
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10099
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10125
[Info   : Unity Log] Spawning Puffo after 113.6307 seconds
[Info   : Unity Log] spawned Puffo in Delayed Wave
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10134
[Info   : Unity Log] spawned 1 monsters
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10143
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10152
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10161
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10170
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10179
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 10188
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10188
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10206
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.005 on frame: 10216
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10234
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10243
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10252
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10261
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10270
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10279
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10288
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10297
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10306
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10315
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10325
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10334
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10340
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10349
[Info   : Unity Log] Content provider HeadBoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 10358
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10358
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10430
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10448
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10457
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10466
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10475
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10484
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10493
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10502
[Info   : Unity Log] Teleporting Puffo(Clone)
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10511
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10520
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10538
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10545
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10554
[Info   : Unity Log] Content provider Weeping(Clone) (WeepingContentProvider) seen amount 0.0025 on frame: 10563
[Error  : Unity Log] Lost Target
[Info   : Unity Log] Spawning Slurper after 132.272 seconds
[Info   : Unity Log] spawned Slurper in Delayed Wave
[Info   : Unity Log] spawned 1 monsters
[Info   : Unity Log] Content provider BoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 11564
[Info   : Unity Log] Content provider BoneArtifact(Clone) (DefaultNamespace.ContentProviders.ArtifactContentProvider) seen amount 0.0025 on frame: 11582
[Info   : Unity Log] Spawning Zombe after 142.5723 seconds
[Info   : Unity Log] spawned Zombe in Delayed Wave
[Info   : Unity Log] spawned 1 monsters
[Info   : Unity Log] Stop recording, camera instance id:867c23e6-3331-459f-9502-7d2676042661, video ID: 5d8c72ca-d2a6-4e8e-8786-ac22706bee63, clip ID: 9235507b-2186-422b-8e39-9408a8905e1c
[Error  : Unity Log] GPU readback error was detected.
[Info   : Unity Log] Running FFmpeg encode... -y -thread_queue_size 512 -r 24 -i C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/Test%04d.png -f f32le -ac 2 -ar 48000 -thread_queue_size 512 -i C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/audio.raw -f f32le -ac 1 -ar 48000 -thread_queue_size 512 -i C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/mic.raw -map 0:0 -map 1:0 -c:a libvorbis -ac 2 -ar 24000 -filter_complex amix=inputs=2 -c:v libvpx -cpu-used -5 -deadline realtime -pix_fmt yuv420p -speed 1 -preset ultrafast C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/output.webm
[Info   : Unity Log] FFmpeg took 8.785s to encode the video.
[Info   : Unity Log] Encoder FFmpeg stderr (exit code 0) ffmpeg version n6.1.1-34-g5e45c27ba9-20240409 Copyright (c) 2000-2023 the FFmpeg developers
  built with gcc 13.2.0 (crosstool-NG 1.26.0.65_ecc5e41)
  configuration: --prefix=/ffbuild/prefix --pkg-config-flags=--static --pkg-config=pkg-config --cross-prefix=x86_64-w64-mingw32- --arch=x86_64 --target-os=mingw32 --enable-version3 --disable-debug --disable-w32threads --enable-pthreads --enable-iconv --enable-libxml2 --enable-zlib --enable-libfreetype --enable-libfribidi --enable-gmp --enable-fontconfig --enable-libharfbuzz --enable-libvorbis --enable-opencl --disable-libpulse --enable-libvmaf --disable-libxcb --disable-xlib --enable-amf --enable-libaom --enable-libaribb24 --disable-avisynth --enable-chromaprint --enable-libdav1d --disable-libdavs2 --disable-libfdk-aac --enable-ffnvcodec --enable-cuda-llvm --disable-frei0r --enable-libgme --enable-libkvazaar --enable-libaribcaption --enable-libass --enable-libbluray --enable-libjxl --enable-libmp3lame --enable-libopus --enable-librist --enable-libssh --enable-libtheora --enable-libvpx --enable-libwebp --enable-lv2 --enable-libvpl --enable-openal --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenh264 --enable-libopenjpeg --enable-libopenmpt --enable-librav1e --disable-librubberband --enable-schannel --enable-sdl2 --enable-libsoxr --enable-libsrt --enable-libsvtav1 --enable-libtwolame --enable-libuavs3d --disable-libdrm --enable-vaapi --disable-libvidstab --enable-vulkan --enable-libshaderc --enable-libplacebo --disable-libx264 --disable-libx265 --disable-libxavs2 --disable-libxvid --enable-libzimg --enable-libzvbi --extra-cflags=-DLIBTWOLAME_STATIC --extra-cxxflags= --extra-libs=-lgomp --extra-ldflags=-pthread --extra-ldexeflags= --cc=x86_64-w64-mingw32-gcc --cxx=x86_64-w64-mingw32-g++ --ar=x86_64-w64-mingw32-gcc-ar --ranlib=x86_64-w64-mingw32-gcc-ranlib --nm=x86_64-w64-mingw32-gcc-nm --extra-version=20240409
  libavutil      58. 29.100 / 58. 29.100
  libavcodec     60. 31.102 / 60. 31.102
  libavformat    60. 16.100 / 60. 16.100
  libavdevice    60.  3.100 / 60.  3.100
  libavfilter     9. 12.100 /  9. 12.100
  libswscale      7.  5.100 /  7.  5.100
  libswresample   4. 12.100 /  4. 12.100
Input #0, image2, from 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/Test%04d.png':
  Duration: 00:01:02.08, start: 0.000000, bitrate: N/A
  Stream #0:0: Video: png, rgba(pc, gbr/unknown/unknown), 420x420, 25 fps, 25 tbr, 25 tbn
[f32le @ 0000020fd0610c00] Estimating duration from bitrate, this may be inaccurate
[aist#1:0/pcm_f32le @ 0000020fd060d800] Guessed Channel Layout: stereo
Input #1, f32le, from 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/audio.raw':
  Duration: 00:01:04.58, bitrate: 3072 kb/s
  Stream #1:0: Audio: pcm_f32le, 48000 Hz, 2 channels, flt, 3072 kb/s
[f32le @ 0000020fd2070100] Estimating duration from bitrate, this may be inaccurate
[aist#2:0/pcm_f32le @ 0000020fd2070cc0] Guessed Channel Layout: mono
Input #2, f32le, from 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/mic.raw':
  Duration: 00:01:04.62, bitrate: 1536 kb/s
  Stream #2:0: Audio: pcm_f32le, 48000 Hz, 1 channels, flt, 1536 kb/s
[out#0/webm @ 0000020fd1b74540] Codec AVOption preset (Encoding preset) has not been used for any stream. The most likely reason is either wrong type (e.g. a video option with no video streams) or that it is a private option of some encoder which was not actually used for any stream.
Stream mapping:
  Stream #1:0 (pcm_f32le) -> amix (graph 0)
  Stream #2:0 (pcm_f32le) -> amix (graph 0)
  amix:default (graph 0) -> Stream #0:0 (libvorbis)
  Stream #0:0 -> #0:1 (png (native) -> vp8 (libvpx))
  Stream #1:0 -> #0:2 (pcm_f32le (native) -> vorbis (libvorbis))
Press [q] to stop, [?] for help
[libvpx @ 0000020fd1b7d9c0] v1.14.0
[libvpx @ 0000020fd1b7d9c0] Neither bitrate nor constrained quality specified, using default CRF of 32 and bitrate of 256kbit/sec
Output #0, webm, to 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c/output.webm':
  Metadata:
    encoder         : Lavf60.16.100
  Stream #0:0: Audio: vorbis, 24000 Hz, stereo, fltp (default)
    Metadata:
      encoder         : Lavc60.31.102 libvorbis
  Stream #0:1: Video: vp8, yuv420p(tv, progressive), 420x420, q=2-31, 256 kb/s, 24 fps, 1k tbn
    Metadata:
      encoder         : Lavc60.31.102 libvpx
    Side data:
      cpb: bitrate max/min/avg: 0/0/0 buffer size: 0 vbv_delay: N/A
  Stream #0:2: Audio: vorbis, 24000 Hz, stereo, fltp
    Metadata:
      encoder         : Lavc60.31.102 libvorbis
frame=    0 fps=0.0 q=12.0 size=       0kB time=00:00:00.00 bitrate=N/A speed=   0x    
[in#0/image2 @ 0000020fd05f9040] Thread message queue blocking; consider raising the thread_queue_size option (current value: 512)
frame=   90 fps=0.0 q=47.0 size=       8kB time=00:00:03.70 bitrate=  17.4kbits/s speed=6.57x    
frame=  177 fps=166 q=42.0 size=     245kB time=00:00:07.33 bitrate= 273.8kbits/s speed=6.89x    
frame=  283 fps=181 q=35.0 size=     256kB time=00:00:11.75 bitrate= 178.5kbits/s speed=7.51x    
frame=  383 fps=185 q=33.0 size=     512kB time=00:00:15.91 bitrate= 263.5kbits/s speed= 7.7x    
frame=  481 fps=187 q=43.0 size=     512kB time=00:00:20.00 bitrate= 209.7kbits/s speed=7.79x    
frame=  578 fps=188 q=63.0 size=     768kB time=00:00:24.04 bitrate= 261.7kbits/s speed=7.84x    
frame=  665 fps=186 q=62.0 size=    1024kB time=00:00:27.66 bitrate= 303.2kbits/s speed=7.75x    
frame=  753 fps=185 q=63.0 size=    1024kB time=00:00:31.37 bitrate= 267.4kbits/s speed=7.71x    
frame=  849 fps=186 q=63.0 size=    1280kB time=00:00:35.37 bitrate= 296.4kbits/s speed=7.74x    
frame=  938 fps=185 q=60.0 size=    1536kB time=00:00:39.04 bitrate= 322.3kbits/s speed= 7.7x    
frame= 1035 fps=186 q=50.0 size=    1792kB time=00:00:43.12 bitrate= 340.4kbits/s speed=7.74x    
frame= 1125 fps=185 q=47.0 size=    1792kB time=00:00:46.83 bitrate= 313.5kbits/s speed=7.72x    
frame= 1223 fps=186 q=59.0 size=    2048kB time=00:00:50.91 bitrate= 329.5kbits/s speed=7.75x    
frame= 1321 fps=187 q=59.0 size=    2304kB time=00:00:55.00 bitrate= 343.2kbits/s speed=7.78x    
frame= 1412 fps=186 q=51.0 size=    2560kB time=00:00:58.79 bitrate= 356.7kbits/s speed=7.76x    
frame= 1510 fps=187 q=58.0 size=    2560kB time=00:01:02.87 bitrate= 333.5kbits/s speed=7.79x    
[out#0/webm @ 0000020fd1b74540] video:2063kB audio:862kB subtitle:0kB other streams:0kB global headers:7kB muxing overhead: 2.197467%
frame= 1552 fps=187 q=63.0 Lsize=    2989kB time=00:01:04.62 bitrate= 378.9kbits/s speed=7.77x    

[Info   : Unity Log] Encoded C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c, 1554 frames, Audio Frames 3027, Audio Data Size 2048, Audio Duration 64.58s, Video Duration 64.75s
[Info   : Unity Log] Begin To Send VideoChunks: 103 Clip: 9235507b-2186-422b-8e39-9408a8905e1c Video: 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   : Unity Log] Sending chunk via steam...1
[Info   : Unity Log] Sending chunk via steam...2
[Info   : Unity Log] Sending chunk via steam...3
[Info   : Unity Log] Sending chunk via steam...4
[Info   : Unity Log] Sending chunk via steam...5
[Info   : Unity Log] Sending chunk via steam...6
[Info   : Unity Log] Sending chunk via steam...7
[Info   : Unity Log] Sending chunk via steam...8
[Info   : Unity Log] Sending chunk via steam...9
[Info   : Unity Log] Sending chunk via steam...10
[Info   : Unity Log] Sending chunk via steam...11
[Info   : Unity Log] Sending chunk via steam...12
[Info   : Unity Log] Sending chunk via steam...13
[Info   : Unity Log] Sending chunk via steam...14
[Info   : Unity Log] Sending chunk via steam...15
[Info   : Unity Log] Sending chunk via steam...16
[Info   : Unity Log] Sending chunk via steam...17
[Info   : Unity Log] Sending chunk via steam...18
[Info   : Unity Log] Sending chunk via steam...19
[Info   : Unity Log] Sending chunk via steam...20
[Info   : Unity Log] Sending chunk via steam...21
[Info   : Unity Log] Sending chunk via steam...22
[Info   : Unity Log] Sending chunk via steam...23
[Info   : Unity Log] Sending chunk via steam...24
[Info   : Unity Log] Sending chunk via steam...25
[Info   : Unity Log] Sending chunk via steam...26
[Info   : Unity Log] Sending chunk via steam...27
[Info   : Unity Log] Sending chunk via steam...28
[Info   : Unity Log] Sending chunk via steam...29
[Info   : Unity Log] Sending chunk via steam...30
[Info   : Unity Log] Sending chunk via steam...31
[Info   : Unity Log] Sending chunk via steam...32
[Info   : Unity Log] Sending chunk via steam...33
[Info   : Unity Log] Sending chunk via steam...34
[Info   : Unity Log] Sending chunk via steam...35
[Info   : Unity Log] Sending chunk via steam...36
[Info   : Unity Log] Sending chunk via steam...37
[Info   : Unity Log] Sending chunk via steam...38
[Info   : Unity Log] Sending chunk via steam...39
[Info   : Unity Log] Sending chunk via steam...40
[Info   : Unity Log] Sending chunk via steam...41
[Info   : Unity Log] Sending chunk via steam...42
[Info   : Unity Log] Sending chunk via steam...43
[Info   : Unity Log] Sending chunk via steam...44
[Info   : Unity Log] Sending chunk via steam...45
[Info   : Unity Log] Sending chunk via steam...46
[Info   : Unity Log] Sending chunk via steam...47
[Info   : Unity Log] Sending chunk via steam...48
[Info   : Unity Log] Sending chunk via steam...49
[Info   : Unity Log] Sending chunk via steam...50
[Info   : Unity Log] Sending chunk via steam...51
[Info   : Unity Log] Sending chunk via steam...52
[Info   : Unity Log] Sending chunk via steam...53
[Info   : Unity Log] Sending chunk via steam...54
[Info   : Unity Log] Sending chunk via steam...55
[Info   : Unity Log] Sending chunk via steam...56
[Info   : Unity Log] Sending chunk via steam...57
[Info   : Unity Log] Sending chunk via steam...58
[Info   : Unity Log] Sending chunk via steam...59
[Info   : Unity Log] Sending chunk via steam...60
[Info   : Unity Log] Sending chunk via steam...61
[Info   : Unity Log] Sending chunk via steam...62
[Info   : Unity Log] Sending chunk via steam...63
[Info   : Unity Log] Sending chunk via steam...64
[Info   : Unity Log] Sending chunk via steam...65
[Info   : Unity Log] Sending chunk via steam...66
[Info   : Unity Log] Sending chunk via steam...67
[Info   : Unity Log] Sending chunk via steam...68
[Info   : Unity Log] Sending chunk via steam...69
[Info   : Unity Log] Sending chunk via steam...70
[Info   : Unity Log] Sending chunk via steam...71
[Info   : Unity Log] Sending chunk via steam...72
[Info   : Unity Log] Sending chunk via steam...73
[Info   : Unity Log] Sending chunk via steam...74
[Info   : Unity Log] Sending chunk via steam...75
[Info   : Unity Log] Sending chunk via steam...76
[Info   : Unity Log] Sending chunk via steam...77
[Info   : Unity Log] Sending chunk via steam...78
[Info   : Unity Log] Sending chunk via steam...79
[Info   : Unity Log] Sending chunk via steam...80
[Info   : Unity Log] Sending chunk via steam...81
[Info   : Unity Log] Sending chunk via steam...82
[Info   : Unity Log] Sending chunk via steam...83
[Info   : Unity Log] Sending chunk via steam...84
[Info   : Unity Log] Sending chunk via steam...85
[Info   : Unity Log] Sending chunk via steam...86
[Info   : Unity Log] Sending chunk via steam...87
[Info   : Unity Log] Sending chunk via steam...88
[Info   : Unity Log] Sending chunk via steam...89
[Info   : Unity Log] Sending chunk via steam...90
[Info   : Unity Log] Sending chunk via steam...91
[Info   : Unity Log] Spawning Ear after 212.9018 seconds
[Info   : Unity Log] spawned Ear in Delayed Wave
[Info   : Unity Log] spawned 1 monsters
[Info   : Unity Log] Sending chunk via steam...92
[Info   : Unity Log] Sending chunk via steam...93
[Info   : Unity Log] Sending chunk via steam...94
[Info   : Unity Log] Sending chunk via steam...95
[Info   : Unity Log] Sending chunk via steam...96
[Info   : Unity Log] Sending chunk via steam...97
[Info   : Unity Log] Sending chunk via steam...98
[Info   : Unity Log] Sending chunk via steam...99
[Info   : Unity Log] Sending chunk via steam...100
[Info   : Unity Log] Sending chunk via steam...101
[Info   : Unity Log] Sending chunk via steam...102
[Info   : Unity Log] Sending chunk via steam...103
[Info   : Unity Log] Clip: 9235507b-2186-422b-8e39-9408a8905e1c has sent!
[Info   : Unity Log] Teleporting Zombe(Clone)
[Error  : Unity Log] Diving Bell is not ready to return to the surface
[Error  : Unity Log] Diving Bell is not ready to return to the surface
[Info   : Unity Log] Switched State to: DivingBellReadyState
[Info   :Found Footage] ReturnToSurface enter
[Info   :Found Footage] ReturnToSurface enter
[Info   : Unity Log] video 5d8c72ca added new clip: 10a0c798, total clips: 2
[Info   : Unity Log] Start recording, camera instance id:867c23e6-3331-459f-9502-7d2676042661, video ID: 5d8c72ca-d2a6-4e8e-8786-ac22706bee63, clip ID: 10a0c798-9cc0-4aed-a2fa-47525122febd
[Info   : Unity Log] Setting camera to send audio to Clip Recorder: 10a
[Info   : Unity Log] Setting sample rate to: 48000
[Info   : Unity Log] Setting channels to 1
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16779
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16788
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16797
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16806
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16815
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16824
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16833
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16842
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16851
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16860
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16869
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16878
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16887
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16896
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16905
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16914
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16923
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16932
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16941
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16950
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16959
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16968
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16977
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16986
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 16995
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17004
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17013
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17022
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17031
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17040
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17049
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17058
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17067
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17076
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17085
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17094
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17103
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17112
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17121
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17130
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17139
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17148
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17157
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17166
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17176
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17185
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17194
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17203
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17212
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17221
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17230
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17239
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17248
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17257
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17266
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9925 on frame: 17273
[Info   : Unity Log] Adding Persistent object: Camera1(Clone)
[Info   : Unity Log] Adding Persistent object: Camera1(Clone)
[Info   : Unity Log] Adding Persistent object: Camera1(Clone)
[Info   : Unity Log] Adding Persistent object: Camera1(Clone)
[Info   : Unity Log] Adding Persistent object: Camera1(Clone)
[Info   : Unity Log] Adding Persistent object: Camera1(Clone)
[Info   : Unity Log] Adding Persistent object: Camera1(Clone)
[Info   : Unity Log] Photon is loading level: SurfaceScene
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17281
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 0.9975 on frame: 17288
[Info   : Unity Log] Content provider DiveBell (13) (PropContentProvider) seen amount 1 on frame: 17289
[Info   : Unity Log] Stop recording, camera instance id:867c23e6-3331-459f-9502-7d2676042661, video ID: 5d8c72ca-d2a6-4e8e-8786-ac22706bee63, clip ID: 10a0c798-9cc0-4aed-a2fa-47525122febd
[Info   : Unity Log] Listener added: ExtractVideoMachine
[Info   : Unity Log] Time of day changed to Evening
[Info   : Unity Log] Switched State to: ExtractMachineIdleState
[Info   : Unity Log] SurfaceNetworkHandler Awake! InRoom : True
[Info   : Unity Log] Listener added: ShopViewScreen
[Warning: Unity Log] Cant find locKey for: Hat_HardHat
[Info   : Unity Log] Listener added: UploadVideoStation
[Error  :Found Footage] Root: UploadMachine2 (UnityEngine.GameObject)
[Error  :Found Footage] SaveVideo: SaveVideo (UnityEngine.GameObject)
[Error  :Found Footage] ReplayInt: ReplayInt (UnityEngine.GameObject)
[Info   : Unity Log] Switched State to: DivingBellNotReadyDoorOpenState
[Info   : Unity Log] Already Found VoiceClient, Destroying...
[Warning: Unity Log] DontDestroyOnLoad only works for root GameObjects or components on root GameObjects.
[Info   : Unity Log] Listener handle for type ItemInstancePackage already exists, removing old handles
[Info   : Unity Log] Listener added: EveningToggler
[Info   : Unity Log] Time of day changed to Evening
[Info   : Unity Log] Switched State to: UploadVideoState
[Info   : Unity Log] Initializing Surface
[Info   : Unity Log] Should do next day here but waiting for upload?
[Info   : Unity Log] Checking Hospital Bill, Dead Players Are:  Total Bill is: 0$
[Info   : Unity Log] Spawning local player: DiveBell
[Info   : Unity Log] Shop Started, Initializing...
[Error  : Unity Log] Failed to get Localized displayName for: Sketch Pad
[Info   : Unity Log] GameLobby Started, Surface: True
[Warning: Unity Log] OnPlayerJoined
[Warning: Unity Log] Player(Clone) is sleeping in bed 0
[Error  : Unity Log] all beds are full
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] Switched State to: DivingBellRechargingState
[Warning: Unity Log] [2024-09-23T12:47:42] [WARNING] [Recorder] [Voice] [PV] MicWrapper: microphone does not support suggested frequency 24000 (min: 48000, max: 48000). Setting to 48000
[Warning: Unity Log] [2024-09-23T12:47:42] [WARNING] [PunVoiceClient] [VoiceClient] [PV] Local voice #5 audio source frequency 48000 and encoder sampling rate 24000 do not match. Resampling will occur before encoding (FramerResampler, interp).
[Info   : Unity Log] visor setting text to: >;3
[Info   : Unity Log] Setting microphone to Microphone (AQIRYS Altair 7.1 Headset)
[Warning: Unity Log] [2024-09-23T12:47:42] [WARNING] [Recorder] [Voice] [PV] MicWrapper: microphone does not support suggested frequency 24000 (min: 48000, max: 48000). Setting to 48000
[Warning: Unity Log] [2024-09-23T12:47:42] [WARNING] [PunVoiceClient] [VoiceClient] [PV] Local voice #6 audio source frequency 48000 and encoder sampling rate 24000 do not match. Resampling will occur before encoding (FramerResampler, interp).
[Info   : Unity Log] Running FFmpeg encode... -y -thread_queue_size 512 -r 24 -i C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/Test%04d.png -f f32le -ac 2 -ar 48000 -thread_queue_size 512 -i C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/audio.raw -f f32le -ac 1 -ar 48000 -thread_queue_size 512 -i C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/mic.raw -map 0:0 -map 1:0 -c:a libvorbis -ac 2 -ar 24000 -filter_complex amix=inputs=2 -c:v libvpx -cpu-used -5 -deadline realtime -pix_fmt yuv420p -speed 1 -preset ultrafast C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/output.webm
[Info   : Unity Log] FFmpeg took 1.143s to encode the video.
[Info   : Unity Log] Encoder FFmpeg stderr (exit code 0) ffmpeg version n6.1.1-34-g5e45c27ba9-20240409 Copyright (c) 2000-2023 the FFmpeg developers
  built with gcc 13.2.0 (crosstool-NG 1.26.0.65_ecc5e41)
  configuration: --prefix=/ffbuild/prefix --pkg-config-flags=--static --pkg-config=pkg-config --cross-prefix=x86_64-w64-mingw32- --arch=x86_64 --target-os=mingw32 --enable-version3 --disable-debug --disable-w32threads --enable-pthreads --enable-iconv --enable-libxml2 --enable-zlib --enable-libfreetype --enable-libfribidi --enable-gmp --enable-fontconfig --enable-libharfbuzz --enable-libvorbis --enable-opencl --disable-libpulse --enable-libvmaf --disable-libxcb --disable-xlib --enable-amf --enable-libaom --enable-libaribb24 --disable-avisynth --enable-chromaprint --enable-libdav1d --disable-libdavs2 --disable-libfdk-aac --enable-ffnvcodec --enable-cuda-llvm --disable-frei0r --enable-libgme --enable-libkvazaar --enable-libaribcaption --enable-libass --enable-libbluray --enable-libjxl --enable-libmp3lame --enable-libopus --enable-librist --enable-libssh --enable-libtheora --enable-libvpx --enable-libwebp --enable-lv2 --enable-libvpl --enable-openal --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenh264 --enable-libopenjpeg --enable-libopenmpt --enable-librav1e --disable-librubberband --enable-schannel --enable-sdl2 --enable-libsoxr --enable-libsrt --enable-libsvtav1 --enable-libtwolame --enable-libuavs3d --disable-libdrm --enable-vaapi --disable-libvidstab --enable-vulkan --enable-libshaderc --enable-libplacebo --disable-libx264 --disable-libx265 --disable-libxavs2 --disable-libxvid --enable-libzimg --enable-libzvbi --extra-cflags=-DLIBTWOLAME_STATIC --extra-cxxflags= --extra-libs=-lgomp --extra-ldflags=-pthread --extra-ldexeflags= --cc=x86_64-w64-mingw32-gcc --cxx=x86_64-w64-mingw32-g++ --ar=x86_64-w64-mingw32-gcc-ar --ranlib=x86_64-w64-mingw32-gcc-ranlib --nm=x86_64-w64-mingw32-gcc-nm --extra-version=20240409
  libavutil      58. 29.100 / 58. 29.100
  libavcodec     60. 31.102 / 60. 31.102
  libavformat    60. 16.100 / 60. 16.100
  libavdevice    60.  3.100 / 60.  3.100
  libavfilter     9. 12.100 /  9. 12.100
  libswscale      7.  5.100 /  7.  5.100
  libswresample   4. 12.100 /  4. 12.100
Input #0, image2, from 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/Test%04d.png':
  Duration: 00:00:08.48, start: 0.000000, bitrate: N/A
  Stream #0:0: Video: png, rgba(pc, gbr/unknown/unknown), 420x420, 25 fps, 25 tbr, 25 tbn
[f32le @ 000002ad43b754c0] Estimating duration from bitrate, this may be inaccurate
[aist#1:0/pcm_f32le @ 000002ad42452500] Guessed Channel Layout: stereo
Input #1, f32le, from 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/audio.raw':
  Duration: 00:00:08.83, bitrate: 3072 kb/s
  Stream #1:0: Audio: pcm_f32le, 48000 Hz, 2 channels, flt, 3072 kb/s
[f32le @ 000002ad43f39580] Estimating duration from bitrate, this may be inaccurate
[aist#2:0/pcm_f32le @ 000002ad43a3d100] Guessed Channel Layout: mono
Input #2, f32le, from 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/mic.raw':
  Duration: 00:00:08.80, bitrate: 1536 kb/s
  Stream #2:0: Audio: pcm_f32le, 48000 Hz, 1 channels, flt, 1536 kb/s
[out#0/webm @ 000002ad4242fdc0] Codec AVOption preset (Encoding preset) has not been used for any stream. The most likely reason is either wrong type (e.g. a video option with no video streams) or that it is a private option of some encoder which was not actually used for any stream.
Stream mapping:
  Stream #1:0 (pcm_f32le) -> amix (graph 0)
  Stream #2:0 (pcm_f32le) -> amix (graph 0)
  amix:default (graph 0) -> Stream #0:0 (libvorbis)
  Stream #0:0 -> #0:1 (png (native) -> vp8 (libvpx))
  Stream #1:0 -> #0:2 (pcm_f32le (native) -> vorbis (libvorbis))
Press [q] to stop, [?] for help
[libvpx @ 000002ad43a5b780] v1.14.0
[libvpx @ 000002ad43a5b780] Neither bitrate nor constrained quality specified, using default CRF of 32 and bitrate of 256kbit/sec
Output #0, webm, to 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd/output.webm':
  Metadata:
    encoder         : Lavf60.16.100
  Stream #0:0: Audio: vorbis, 24000 Hz, stereo, fltp (default)
    Metadata:
      encoder         : Lavc60.31.102 libvorbis
  Stream #0:1: Video: vp8, yuv420p(tv, progressive), 420x420, q=2-31, 256 kb/s, 24 fps, 1k tbn
    Metadata:
      encoder         : Lavc60.31.102 libvpx
    Side data:
      cpb: bitrate max/min/avg: 0/0/0 buffer size: 0 vbv_delay: N/A
  Stream #0:2: Audio: vorbis, 24000 Hz, stereo, fltp
    Metadata:
      encoder         : Lavc60.31.102 libvorbis
frame=    0 fps=0.0 q=12.0 size=       0kB time=00:00:00.00 bitrate=N/A speed=   0x    
frame=  107 fps=0.0 q=35.0 size=       8kB time=00:00:04.41 bitrate=  14.6kbits/s speed=8.08x    
[out#0/webm @ 000002ad4242fdc0] video:239kB audio:110kB subtitle:0kB other streams:0kB global headers:7kB muxing overhead: 4.360192%
frame=  212 fps=209 q=37.0 Lsize=     365kB time=00:00:08.81 bitrate= 339.0kbits/s speed= 8.7x    

[Info   : Unity Log] Encoded C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd, 214 frames, Audio Frames 414, Audio Data Size 2048, Audio Duration 8.83s, Video Duration 8.92s
[Info   : Unity Log] Begin To Send VideoChunks: 13 Clip: 10a0c798-9cc0-4aed-a2fa-47525122febd Video: 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   : Unity Log] Sending chunk via steam...1
[Info   : Unity Log] Sending chunk via steam...2
[Info   : Unity Log] Sending chunk via steam...3
[Info   : Unity Log] Sending chunk via steam...4
[Info   : Unity Log] Sending chunk via steam...5
[Info   : Unity Log] Sending chunk via steam...6
[Info   : Unity Log] Sending chunk via steam...7
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Found dislike sprite: Skull-1--Streamline-Ultimate (1) (UnityEngine.Sprite)
[Info   :Found Footage] Found like sprite: Emoji-Great--Streamline-Ultimate (UnityEngine.Sprite)
[Info   : Unity Log] Sending chunk via steam...8
[Info   : Unity Log] Sending chunk via steam...9
[Info   : Unity Log] Sending chunk via steam...10
[Info   : Unity Log] Sending chunk via steam...11
[Info   : Unity Log] Sending chunk via steam...12
[Info   : Unity Log] Sending chunk via steam...13
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   :Found Footage] Check IsLocal
[Info   : Unity Log] Clip: 10a0c798-9cc0-4aed-a2fa-47525122febd has sent!
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   :Found Footage] Check IsLocal
[Info   : Unity Log] Switched State to: ExtractMachineCheckItemState
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Found pickup: Camera
[Info   : Unity Log] FOUND CAMERA
[Info   : Unity Log] Switched State to: ExtractMachineExtractingState
[Info   : Unity Log] Found pickup: Camera
[Info   : Unity Log] EXTRACT! video=5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] REAAADDYYY STARTING EXTRACT!
[Info   : Unity Log] All clips ready, starting stitching...
[Info   : Unity Log] Stitching videos together: file 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\9235507b-2186-422b-8e39-9408a8905e1c\output.webm'
file 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\10a0c798-9cc0-4aed-a2fa-47525122febd\output.webm'

[Info   : Unity Log] Starting FFmpegStitcher: -y -f concat -safe 0 -i C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\videoList.txt -c copy C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\fullRecording.webm
[Info   : Unity Log] Video stitch ffmpeg stderr (exit code 0): ffmpeg version n6.1.1-34-g5e45c27ba9-20240409 Copyright (c) 2000-2023 the FFmpeg developers
  built with gcc 13.2.0 (crosstool-NG 1.26.0.65_ecc5e41)
  configuration: --prefix=/ffbuild/prefix --pkg-config-flags=--static --pkg-config=pkg-config --cross-prefix=x86_64-w64-mingw32- --arch=x86_64 --target-os=mingw32 --enable-version3 --disable-debug --disable-w32threads --enable-pthreads --enable-iconv --enable-libxml2 --enable-zlib --enable-libfreetype --enable-libfribidi --enable-gmp --enable-fontconfig --enable-libharfbuzz --enable-libvorbis --enable-opencl --disable-libpulse --enable-libvmaf --disable-libxcb --disable-xlib --enable-amf --enable-libaom --enable-libaribb24 --disable-avisynth --enable-chromaprint --enable-libdav1d --disable-libdavs2 --disable-libfdk-aac --enable-ffnvcodec --enable-cuda-llvm --disable-frei0r --enable-libgme --enable-libkvazaar --enable-libaribcaption --enable-libass --enable-libbluray --enable-libjxl --enable-libmp3lame --enable-libopus --enable-librist --enable-libssh --enable-libtheora --enable-libvpx --enable-libwebp --enable-lv2 --enable-libvpl --enable-openal --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenh264 --enable-libopenjpeg --enable-libopenmpt --enable-librav1e --disable-librubberband --enable-schannel --enable-sdl2 --enable-libsoxr --enable-libsrt --enable-libsvtav1 --enable-libtwolame --enable-libuavs3d --disable-libdrm --enable-vaapi --disable-libvidstab --enable-vulkan --enable-libshaderc --enable-libplacebo --disable-libx264 --disable-libx265 --disable-libxavs2 --disable-libxvid --enable-libzimg --enable-libzvbi --extra-cflags=-DLIBTWOLAME_STATIC --extra-cxxflags= --extra-libs=-lgomp --extra-ldflags=-pthread --extra-ldexeflags= --cc=x86_64-w64-mingw32-gcc --cxx=x86_64-w64-mingw32-g++ --ar=x86_64-w64-mingw32-gcc-ar --ranlib=x86_64-w64-mingw32-gcc-ranlib --nm=x86_64-w64-mingw32-gcc-nm --extra-version=20240409
  libavutil      58. 29.100 / 58. 29.100
  libavcodec     60. 31.102 / 60. 31.102
  libavformat    60. 16.100 / 60. 16.100
  libavdevice    60.  3.100 / 60.  3.100
  libavfilter     9. 12.100 /  9. 12.100
  libswscale      7.  5.100 /  7.  5.100
  libswresample   4. 12.100 /  4. 12.100
Input #0, concat, from 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\videoList.txt':
  Duration: N/A, start: 0.000000, bitrate: N/A
  Stream #0:0: Audio: vorbis, 24000 Hz, stereo, fltp
    Metadata:
      ENCODER         : Lavc60.31.102 libvorbis
      DURATION        : 00:01:04.631000000
  Stream #0:1: Video: vp8, yuv420p(tv, progressive), 420x420, SAR 1:1 DAR 1:1, 24 fps, 24 tbr, 1k tbn
    Metadata:
      ENCODER         : Lavc60.31.102 libvpx
      DURATION        : 00:01:04.678000000
  Stream #0:2: Audio: vorbis, 24000 Hz, stereo, fltp
    Metadata:
      ENCODER         : Lavc60.31.102 libvorbis
      DURATION        : 00:01:04.587000000
Output #0, webm, to 'C:\Users\Windows\AppData\Local\Temp\rec\5d8c72ca-d2a6-4e8e-8786-ac22706bee63\fullRecording.webm':
  Metadata:
    encoder         : Lavf60.16.100
  Stream #0:0: Video: vp8, yuv420p(tv, progressive), 420x420 [SAR 1:1 DAR 1:1], q=2-31, 24 fps, 24 tbr, 1k tbn
    Metadata:
      ENCODER         : Lavc60.31.102 libvpx
      DURATION        : 00:01:04.678000000
  Stream #0:1: Audio: vorbis, 24000 Hz, stereo, fltp
    Metadata:
      ENCODER         : Lavc60.31.102 libvorbis
      DURATION        : 00:01:04.631000000
Stream mapping:
  Stream #0:1 -> #0:0 (copy)
  Stream #0:0 -> #0:1 (copy)
Press [q] to stop, [?] for help
size=       0kB time=00:00:00.00 bitrate=N/A speed=N/A    
[out#0/webm @ 0000018d831df9c0] video:2302kB audio:478kB subtitle:0kB other streams:0kB global headers:4kB muxing overhead: 1.513388%
size=    2823kB time=00:01:13.50 bitrate= 314.6kbits/s speed=1.03e+03x    

[Info   : Unity Log] Switched State to: ExtractMachineEjectState
[Info   : Unity Log] EVERYONE DONE!
[Info   :Found Footage] RPC_Success shitted
[Info   :Found Footage] Check 5d8c72ca-d2a6-4e8e-8786-ac22706bee63
[Info   :Found Footage] Do not uploading extracted
[Info   : Unity Log] Switched State to: ExtractMachineIdleState
[Info   : Unity Log] stashAbleEntry entry not found, adding new entry with true.
[Info   : Unity Log] Uploading Videohandle... Evaluating views...
[Info   : Unity Log] Original score: 8.589127, Copied score: 8.589127, Buffer Size: 80 bytes
[Info   : Unity Log] Original score: 1.194887, Copied score: 1.194887, Buffer Size: 22 bytes
[Info   : Unity Log] Recording score: 9.784014
[Info   : Unity Log] Switched State to: UploadCompleteState
[Info   : Unity Log] Evaluation complete. Score: 9.784014
[Info   : Unity Log] Comment count: 4
[Info   : Unity Log] Comment: That big cage guy is real scary
[Info   : Unity Log] Comment: ew is that a human skull?
[Info   : Unity Log] Comment: Never thought I'd be spooked by anatomy, but here we are. Bones, you got me! ??
[Info   : Unity Log] Comment: I wish I had a diving bell
[Info   :Found Footage] UploadCompleteUI.PlayVideo is CameraRecording
[Info   : Unity Log] Last Time: 73.54166
[Info   : Unity Log] Displaying comment: That big cage guy is real scary
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] Check ProcessedFakeVideos
[Info   : Unity Log] Displaying comment: ew is that a human skull?
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] Check ProcessedFakeVideos
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   : Unity Log] Switched State to: ExtractMachineCheckItemState
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] FOUND SOMETHING ELSE
[Info   : Unity Log] Switched State to: ExtractMachineEjectState
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Switched State to: ExtractMachineIdleState
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   :Found Footage] Check ProcessedFakeVideos
[Info   :Found Footage] InitCamera shitting from player
[Info   :Found Footage] Handling 7fffffff-12ba-43ca-a692-3082d0566046
[Info   :Found Footage] Check IsLocal
[Info   :Found Footage] Check FakeVideos
[Info   :Found Footage] Check playerView
[Info   : Unity Log] Switched State to: ExtractMachineCheckItemState
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Hatch is fully closed
[Info   : Unity Log] Found pickup: Camera
[Info   : Unity Log] FOUND CAMERA
[Info   : Unity Log] Switched State to: ExtractMachineExtractingState
[Info   : Unity Log] Found pickup: Camera
[Info   : Unity Log] EXTRACT! video=7fffffff-12ba-43ca-a692-3082d0566046
[Info   : Unity Log] Hatch is fully closed
[Error  : Unity Log] Failed to get recording!: 7fffffff-12ba-43ca-a692-3082d0566046
[Info   : Unity Log] Setting Quota To: 100 From: 0
[Info   : Unity Log] Player: 1 FAILED!
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] Displaying comment: Never thought I'd be spooked by anatomy, but here we are. Bones, you got me! ??
[Info   : Unity Log] Displaying comment: I wish I had a diving bell
[Info   : Unity Log] Setting Quota To: 110 From: 100
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
[Info   : Unity Log] MasterClient Should Not Update RoomStats!
