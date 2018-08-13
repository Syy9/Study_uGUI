## Study_uGUI
study uGUI

## Usage
1. Git clone and open unity project
2. Import asset from AssetStore
[Flat Icoon & UI - 2D Puzzle Game UI](https://assetstore.unity.com/packages/2d/gui/icons/flat-icoon-ui-2d-puzzle-game-ui-69370)
3. Import asset from AssetStore [DoTween](https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676)

## Demo
|demo|description|
|:--:|:--|
|![demo](ReadmeResource/demo01.gif)|demo01.<br>demo which divided UI into parts of header, contents, footer and set pivot & anchor respectively. Therefore, even if the screen size changes, the rough position is not changed|
|![demo](ReadmeResource/demo02.gif)|demo02.<br>Scrollbar demo|
|![demo](ReadmeResource/demo03.gif)|demo03.<br>Gauge bar move by tween of scale.x. Gauge bar anchor is stretch mode and Pivot is (0,0.5). so , if scale.x is 0, width is 0. scale.x is 1, width is gauge body width.<br>If you control the width of the gauge bar directly by the program, you need to know the maximum gauge width, but this method is simple as it just moves the scale from 0 to 1.|
|![demo](ReadmeResource/demo04.gif)|demo04.<br>Expand text body UI. Parent of Text UI have Vertical Layout Group and Content Size Fitter Component. Text Component will update Preferred Width and Height to match the number of characters in your Text. And the Vertical Layout Group (Child Control Size Checked) updates the size of the child element (Text UI) according to Preferred Width and Height. Therefore, as Text characters increases, the size of the parent  also increases.|
|![demo](ReadmeResource/demo05.gif)|demo05.<br>Auto Layout Balloon GUI|

## Library , Assets
* [Flat Icoon & UI - 2D Puzzle Game UI](https://assetstore.unity.com/packages/2d/gui/icons/flat-icoon-ui-2d-puzzle-game-ui-69370)
* [DoTween](https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676)
* [FUKIDASHI DESIGN](http://fukidesign.com/)

## License Logo

![logo](logo.png)
