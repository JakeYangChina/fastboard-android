# Change Log

## [Version 1.2.3] - 2021-08-03
- Fix: `MemberState` some fields cannot be saved locally

## [Version 1.2.2] - 2021-07-28
- Fix: the minimum compileSdk problem caused by core:core-ktx in example.

## [Version 1.2.1] - 2021-06-13

- Fix: `FastInsertDocParams(String taskUUID, String taskToken, String fileType)` parameter sequence
  error
- New: `FastInsertDocParams.dynamicDoc` and `FastInsertDocParams.converterType` to support
  Projector-Conversion docs
- **Breaking Change**: rename `FastRoom.setStokeWidth` to `FastRoom.setStrokeWidth`

## [Version 1.2.0] - 2021-05-07

- Fix: fix get resources NullPointerException on customized `RoomControllerGroup`
- Fix: fix `FastRoom.setFastStyle` only update internal `RoomController` views
- New: add `FastUiSettings.setToolsXXX` to config colors and appliances. **Important Note** these
  config methods should be call before join room.
- Update: initialize the window scale without additional calls `Fastboard.setWhiteboardRatio`.
- **Breaking Change**: replace `ResourceImpl` with `FastResource`

## [Version 1.1.0] - 2021-04-11

- Fix: fix `ToolBox` selected state when overlay hide
- New: add `FastRoomListener`.`onRoomPhaseChanged`
- New: add `FastUiSettings.showRoomController`
- **Breaking Change**: update `FastUiSettings.hideRoomController`, replace resId with `ControllerId`

## [Version 1.0.0] - 2021-03-20

- Update: treat `FastRoom` as main apis class

## [Version 1.0.0-beta.5] - 2021-03-14

- Update: update `FastRoomOptions.fastRegion` required
- Update: remove `FastInsertDocParams.resource`

## [Version 1.0.0-beta.4] - 2021-03-11

- Update: update Samples
- Update: update default ErrorHandle with ErrorHandleLayout
- Update: replace FastSdk with Fastboard
- Update: redefine all Player to Replay
- Update: combine FastListener RoomState apis

## [Version 1.0.0-beta.3] - 2021-02-16

- New: add FastboardView.setWhiteboardRatio
- New: add ResourceImpl for configuration

## [Version 1.0.0-beta.2] - 2021-01-25

- New: add Listener.onWindowBoxStateChanged
- New: add UiSettings.setRedoUndoOrientation
- Update: update Samples
- Update: remove RoomControllerGroup.setupView
- Update: remove FastSdk.setOverlayManager

## [Version 1.0.0-beta.1] - 2021-01-14

- New: basic fastboard concepts
- New: some examples