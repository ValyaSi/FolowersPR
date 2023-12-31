# Changelog

## [[1.0.0d SNAPSHOT (build 220606199)]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-1.0.0d.220606199-SNAPSHOT.zip) - 2022-06-06

### Known issues
  - Shared cross on grafana 8.x (minor)
  - Flow animation on arrows (minor)
  - External image from diagrams.net not displayed (minor)
### Added
  - Convert sync method to async : render graph before update states (x2 faster) 
  - clean dirty code
  - Support last version of grafana (8.5.x)
  - New initialization engine for drawio libs
  - New draw.io libs (17.x 2022-04-23)
  - New notifier handler in panel.
  - Change default url draw.io with https://embed.diagrams.net
  - New edit design for grafana v7-8 ([See example](https://algenty.github.io/flowcharting-repository/images/rulesv7_ani.png?raw=true))
  - New UX design and new concept "fast edit" :
    - Can edit without expand rules and flowcharts with icons
    - Advanced/detail mode on expand.
    - Fast edit mode
  - Add shape name and properties in inspect console ([See example](https://algenty.github.io/flowcharting-repository/images/inspectv7_ani.png?raw=true))  
  - Add gaugePos property in Event Mapping for the gauge draw.io models [See example](https://algenty.github.io/flowcharting-repository/images/gaugePos_ani.png?raw=true))  
  - Plugin is signed
  - Add Light theme support
  - New thresholds type : dates (accept units like d, w, m, y, h, s or a date)
  - New event mapping operators
  - Enable/Disable rule/state/mapping independently.
  - Colors (threshold and background) can be empty.
  
  
### Fixed
  - Fixed : Inspect mode [(issue #209)](https://github.com/algenty/grafana-flowcharting/issues/209) ([See example](https://algenty.github.io/flowcharting-repository/images/inspectv7_ani.png?raw=true))  
  - Fixed : Label position in shape [(issue #147)](https://github.com/algenty/grafana-flowcharting/issues/147)   
  - Fixed : Initialization of first model
  - Fixed : Display refresh between "edit mode" and "dashboard mode" in grafana v7 [(issue #205)](https://github.com/algenty/grafana-flowcharting/issues/205)  
  - Fixed : zoom on text without witdth and height
  - Fixed : Disable select text when double click for zoom
  - Fixed : retro compatibility with grafana 6.x [(issue #218)](https://github.com/algenty/grafana-flowcharting/issues/218)  
  - Fixed : Zoom with 2 or more FlowCharting [(issue #214)](https://github.com/algenty/grafana-flowcharting/issues/214)  
  - Fixed : Background color edition in flowchart tab


## [[1.0.0b SNAPSHOT]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-1.0.0b-SNAPSHOT.zip) - 2020-12-08

### TODO
  - Disable anim not work
  - display zoom percent
  - align icons
  - Size of plugin
  - Styles on firefox

### Added
  - New initialization engine for drawio libs
  - New draw.io libs (13.10.9)
  - New notifier handler in panel.
  - Change default url draw.io with https://embed.diagrams.net
  - New edit design for grafana v7 ([See example](https://algenty.github.io/flowcharting-repository/images/rulesv7_ani.png?raw=true))
  - New UX design and new concept "fast edit" :
    - Can edit without expand rules and flowcharts with icons
    - Advanced/detail mode on expand.
    - Fast edit mode
  - Add shape name and properties in inspect console ([See example](https://algenty.github.io/flowcharting-repository/images/inspectv7_ani.png?raw=true))  
  - Add gaugePos property in Event Mapping for the gauge draw.io models [See example](https://algenty.github.io/flowcharting-repository/images/gaugePos_ani.png?raw=true))  
  - Plugin is signed
  - Add Light theme support
  - New thresholds type : dates (accept units like d, w, m, y, h, s or a date)
  - New event mapping operators
  - Can Enable/Disable each element.
  - Colors (threshold and background) can be empty.
  
### Fixed
  - Fixed : Inspect mode [(issue #209)](https://github.com/algenty/grafana-flowcharting/issues/209) ([See example](https://algenty.github.io/flowcharting-repository/images/inspectv7_ani.png?raw=true))  
  - Fixed : Label position in shape [(issue #147)](https://github.com/algenty/grafana-flowcharting/issues/147)   
  - Fixed : Initialization of first model
  - Fixed : Display refresh between "edit mode" and "dashboard mode" in grafana v7 [(issue #205)](https://github.com/algenty/grafana-flowcharting/issues/205)  
  - Fixed : zoom on text without witdth and height
  - Fixed : Disable select text when double click for zoom
  - Fixed : retro compatibility with grafana 6.x [(issue #218)](https://github.com/algenty/grafana-flowcharting/issues/218)  
  - Fixed : Zoom with 2 or more FlowCharting [(issue #214)](https://github.com/algenty/grafana-flowcharting/issues/214)  
  - Fixed : Background color edition in flowchart tab
## [[0.9.1b SNAPSHOT]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.9.1b-SNAPSHOT.zip) - 2020-11-08
### Added
  - New initialization engine for drawio libs
  - New notifier handler in panel.
  - Change default url draw.io by https://embed.diagrams.net
  - New edit design for grafana v7 ([See example](https://algenty.github.io/flowcharting-repository/images/rulesv7_ani.png?raw=true))  
  - Add shape name and properties in inspect console ([See example](https://algenty.github.io/flowcharting-repository/images/inspectv7_ani.png?raw=true))  
  - Add gaugePos property in Event Mapping for the gauge draw.io models [See example](https://algenty.github.io/flowcharting-repository/images/gaugePos_ani.png?raw=true))  
  
### Fixed
  - Fixed : Inspect mode [(issue #209)](https://github.com/algenty/grafana-flowcharting/issues/209) ([See example](https://algenty.github.io/flowcharting-repository/images/inspectv7_ani.png?raw=true))  
  - Fixed : Label position in shape [(issue #147)](https://github.com/algenty/grafana-flowcharting/issues/147)   
  - Fixed : Initialization of first model
  - Fixed : Display refresh between "edit mode" and "dashboard mode" in grafana v7 [(issue #205)](https://github.com/algenty/grafana-flowcharting/issues/205)  
  - Fixed : zoom on text without witdth and height
  - Fixed : Disable select text when double click for zoom
  - Fixed : retro compatibility with grafana 6.x [(issue #218)](https://github.com/algenty/grafana-flowcharting/issues/218)  
  - Fixed : Zoom when with 2 or mode panels with flowcharting [(issue #214)](https://github.com/algenty/grafana-flowcharting/issues/214) 

## [[0.9.0 SNAPSHOT]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.9.0-SNAPSHOT.zip) - 2020-05-31  
### Added
  - CSV Format support for flowchart source (https://drawio-app.com/import-from-csv-to-drawio/)
  - New aggregation : Time of last point  
  - New fill Method : Gradient ([See example](https://github.com/algenty/grafana-flowcharting/blob/master/src/img/gradients_color_ani2.gif?raw=true))  
  - Graph hover support ([See example](https://github.com/algenty/grafana-flowcharting/blob/master/src/img/floorplan_graphhover.gif?raw=true))  
  - Better rendering of color animation with chroma-js
  - New Events/Animations Mapping :
    * Modify Gradient direction  
    * Modify Arrow start and end connectors ([See example](https://github.com/algenty/grafana-flowcharting/blob/master/src/img/connectors_color_ani2.gif?raw=true))  
    * Flip shape horizontally or vertically  
    * Resize shape in percent ([See example](https://github.com/algenty/grafana-flowcharting/blob/master/src/img/resize_ani.gif?raw=true))  
    * Flow animation (experimental, not work with a shadow on arrow)  
  - New homepage schema
  - Support external fonts like google fonts ([See example](https://github.com/algenty/grafana-flowcharting/blob/master/src/img/google_fonts.png?raw=true))  
  - New anonymizer feature in inspect section ([See example](https://github.com/algenty/grafana-flowcharting/blob/master/src/img/anonymize_ani.gif?raw=true))  
  
### Fixed
  - Fixed : Flowchart grid display  
  - Fixed : background color field  
  - Fixed : Blink event  
  - Fixed : Data is null
  - Fixed : Overflow on grafana v7 [(issue #172)](https://github.com/algenty/grafana-flowcharting/issues/172)   
  
## [[0.8.1]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.8.1.zip) - 2020-05-11  
### Added
  - New plugin logo for Grafana V7 ([See example](https://github.com/algenty/grafana-flowcharting/blob/master/src/img/agenty-flowcharting.png?raw=true))  
    
### Fixed
  - Fixed : Dashboard variables.  
  - Optimize perf and size (7 Mo instead 15 Mo).  
  

## [[0.8.0]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.8.0.zip) - 2020-05-02  
### Add
  - Add Identification by Value/lable in field 'what' in rules (experimental)  
  - Upgrade Draw.io libs (13.0.1)
  - Add option to disable regex/eval for more efficient.  
  - Add 2 new color modes in Color mapping section :  
    - "Label background"  
    - "Label borber"  
  - Add Execution times stats to optimize rules.  
  - Foldable container without disable lock.  
  - Add New custom variables for supported fields (Text Mapping 'with', Link Mapping 'Url' and Event Mapping 'Value'):  
    - ${_value} : raw value  
    - ${_formatted} : formatted value  
    - ${_level} : current level  
    - ${_rule} : name of current rule  
  - Add New Feature :  Events / Animations Mapping, according the level ([See example](https://algenty.github.io/flowcharting-repository/images/all_events_ani.png))  
    - Change shapes form  
    - Change size, opacity, rotation, ...   
    - Hide/Blink shapes  
    - And [more...](https://algenty.github.io/flowcharting-repository/EVENTS)
### Fix
  - Log scale, thanks Dennis [(issue #68)](https://github.com/algenty/grafana-flowcharting/issues/68)  
  - shape stills select when deleting map.
  - select list (typeahead) in fields 'whats' and map values for string type in rules
  - Level State with range or value mapping.
  - Lock always true in flowchart option [(issue #68)](https://github.com/algenty/grafana-flowcharting/issues/138) 
  - Fix Remove link
  - Fix range value Min and Max range when 'from' or 'to' is empty
  - Fix 'With' field in text mapping, empty after clone or save/reload

## [[0.7.0]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.7.0.zip) - 2020-03-25  
### Added  
  - new conditions and design in rule for each mapping instead one by rule ([See example](https://algenty.github.io/flowcharting-repository/images/what_when_how.png))  
    - when : When condition applied  
    - what : which shape  
    - how : how to colorize shape 
    - and more ...
  - Multi colors for thresholds with type number and string ([See example](https://algenty.github.io/flowcharting-repository/images/multicolor_ani.png))
  - Gradient color mode ([See example](https://algenty.github.io/flowcharting-repository/images/floorplan_gradient_gradient.gif))
  - Enable/disable animation like fade color for best performance or best render in 'Direct link rendered image'  
  - Update libs :
    - draw.io : 12.8.6 (Kubernetes shapes and more)  
    - mxgraph : 4.1.0  
### Fixed  
  - Fix getNames for series [(issue #100)](https://github.com/algenty/grafana-flowcharting/issues/100)  
  - Fix colors when cloned rules [(issue #124)](https://github.com/algenty/grafana-flowcharting/issues/124)  
  - Fix shapes with last versions of draw.io [(issue #125)](https://github.com/algenty/grafana-flowcharting/issues/125)  
  - Fix 'Direct link rendered image' [(issue #114)](https://github.com/algenty/grafana-flowcharting/issues/114)  

## [[0.6.1]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.6.1.zip) - 2020-01-15  
### Fixed
  - Fix endless loading when edit graph [(issue #102)](https://github.com/algenty/grafana-flowcharting/issues/102)
  - Fix error on edit mode for timeserie [(issue #100)](https://github.com/algenty/grafana-flowcharting/issues/100)
  - Fix "Apply button" in inspect mode [(issue #104)](https://github.com/algenty/grafana-flowcharting/issues/104)

## [[0.6.0]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.6.0.zip) - 2019-12-21  
### Added  
  - Experimental implementation for table type data (Mysql, Postgres, Zabbix, Streaming, loki and other ...)
  - PlaceHolder feature supported [see doc from draw.io](https://desk.draw.io/support/solutions/articles/16000051979)
  - Some optimization on : 
    - tooltips
    - States
  - Tooltip Graph :
    - Histogram ([See example](https://algenty.github.io/flowcharting-repository/images/histogram_ani.png))
  - Variables support in download input url ([See example](https://algenty.github.io/flowcharting-repository/images/url_download_variable_ani.png))
  - Add graduate animation when color changed ([See example](https://video.twimg.com/tweet_video/EISkJwdWwAAi5Qh.mp4))
  - New rule design in editor ([See example](https://algenty.github.io/flowcharting-repository/images/rule_design.png))
  - Typescript migration for best quality code.
  - Build migration to grafana-toolkit (thanks Dominik and Ryan).
  - New engine graph for best compatibility with draw.io.
  - Better Zoom for firefox and IE/edge.
  - Add checks/controls on edit mode for XML and URL.
  - Regular expression for String type values implemented to define level state.
### Fixed
  - Fix download url on first load.
  - Fix value null for string [(issue #65)](https://github.com/algenty/grafana-flowcharting/issues/65)
  - Fix bug "subways" Editor [(issue #73)](https://github.com/algenty/grafana-flowcharting/issues/73)
  - Fix date on 2 digit in tooltip [(issue #77)](https://github.com/algenty/grafana-flowcharting/issues/73)
  - Fix minors bug.

## [[0.5.0]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.5.0.zip) - 2019-10-15
### Added  
  - 2 new modes for "Update text value" ([See example](https://algenty.github.io/flowcharting-repository/images/append_mode_ani.png))
    - Append (Space) : Concat metrics with a space as a separator
    - Append (New line) : Concat metrics with a line break
  - Variabilization in "Url" for link mapping ([See example](https://algenty.github.io/flowcharting-repository/images/variable_link_ani.png))
  - New check box to allow download images from draw.io ([See example](https://algenty.github.io/flowcharting-repository/images/drawio_source_ani.png))
  - New editor option :
    - Other editor draw.io like internal website draw.io are supported
    - Choose the theme of editor
  - New identification mode for shapes when mouse cursor is over the rules or the mapping ([See example](https://algenty.github.io/flowcharting-repository/images/identification_mode_ani.png))
  - Support Dynamic shapes like Floorplan, isometric plans and more ([See example](https://algenty.github.io/flowcharting-repository/images/dynamic_shapes_ani.png))
  - New color mode for no SVG object like pictures/cliparts/images ([See example](https://algenty.github.io/flowcharting-repository/images/colormode_ani.png))
  - Graphs in tooltip ([See example](https://algenty.github.io/flowcharting-repository/images/tooltip_graph.png))
    - Color graph with defined colors in threshold
    - Size of graph ([See example](https://algenty.github.io/flowcharting-repository/images/graph_size.png))
  - Define the orientation in  tooltip for each metrics/graph in tooltips : horizontal or vertical ([See example](https://algenty.github.io/flowcharting-repository/images/tooltip_direction_ani.png))
  - Some optimizations, Display is twice as fast on load.

### Fixed  
  - Fix color to reset when "Color on" is "Always/Critical" and metric is OK  
  - Fix border to empty instead black when "color mode" is "Fill" [(issue #24)](https://github.com/algenty/grafana-flowcharting/issues/24)  
  - Fix error when "Value On" is not "When metric displayed"
  - Fix Link [(issue #37)](https://github.com/algenty/grafana-flowcharting/issues/37)  
  - Fix hyperlink text appears in white over flowchart [(issue #45)](https://github.com/algenty/grafana-flowcharting/issues/45)
  - Fix "Multiple FlowCharts On a Dashboard", when edit, both are the same draw [(issue #48)](https://github.com/algenty/grafana-flowcharting/issues/48)
  - Fix options after reload or variable changed [(issue #44)](https://github.com/algenty/grafana-flowcharting/issues/48)
  - Fix auto reset zoom/unzoom when data refreshed, only ESC or change options on flowchart reset zoom now [(issue #38)](https://github.com/algenty/grafana-flowcharting/issues/38)
  - Fix error for BPNM shapes [(Issue #51)](https://github.com/algenty/grafana-flowcharting/issues/51)
  - Fix display when center and scale are checked on flowchart options.
  - Fix Zoom with mouse wheel for firefox and Edge.


## [[0.4.0]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.4.0.zip) - 2019-09-26
### Added
  - Draw.io editor ([see example](https://algenty.github.io/flowcharting-repository/images/openEditor_ani.gif))
    - Open draw.io with dark theme for better rendering  
    - Display waiting screen when loading xml definition.  
  - Upgrading libraries  
    - mxGraph 4.0.4  
    - draw.io 11.2.8  
  - Graph definition  
    - Adding download function to download source by http on load. ([See example](https://algenty.github.io/flowcharting-repository/images/download_ani.gif))
  - Metric
    - Adding string support for state (See example)
  - Zoom [(issue #19)](https://github.com/algenty/grafana-flowcharting/issues/19) ([See example](https://algenty.github.io/flowcharting-repository/images/zoom2_ani.gif))
    - On the mouse pointer : Ctrl + Mouse
    - Hold right button to move diagram.
    - double click on shape to zoom on.
    - Escape key to restore.
  - Tooltip/popup support ([see example](https://algenty.github.io/flowcharting-repository/images/tooltip2_ani.gif))
    - Grafana style css and date
    - Adding metrics with color according levels
    - Adding colors on metrics in tooltip
    - Adding date of change
    - Adding label input for metric
  - Variables/templates support, accept variable like ${} ([See example](https://algenty.github.io/flowcharting-repository/images/variable_ani.gif)) 
    - In xml definition
    - In text mapping when type in sring for "Range to text" and "Value to text"
    - In link ovewrite
  - full shapes from draw.io included ([See example](https://algenty.github.io/flowcharting-repository/images/shapes_ani.gif))
  - Some optimizations

### Fixed  
  - Optimization when refresh/render [(issue #15)](https://github.com/algenty/grafana-flowcharting/issues/15)  
  - No decimal fixed when 0 [(issue #23)](https://github.com/algenty/grafana-flowcharting/issues/23)
  - Text substring and color [(issues #29)](https://github.com/algenty/grafana-flowcharting/issues/29)
  - Fix formatted text when label is html [(issues #21)](https://github.com/algenty/grafana-flowcharting/issues/29)
  - Work around a bug since Grafana 6+ [(issues 19426 grafana)](https://github.com/grafana/grafana/issues/19426)

## [[0.3.0]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.3.0.zip) - 2019-05-07
### Added
    
  - Migration process for next release.
  - Dynamic documentation/Examples on popover (thx SCHKN)
  - Params link option, add params of dashboard to link.
  - Full review of code (ES6 Class mode)
  - Unit test with jest to increase quality
  - Fill/text/stoke rules on the same object is possible.
  - Mapping selector helper (chain in mapping)
  - Icon overlay state (display icon warning when NOK)
  - Implemented the conditions to display text according to the states.
  - new inspect Tab with :
    - Renamer ID (double click on ID)
    - State status
    - Debug mode
  - Custom Link Mapping overrite.  
  
### Fixed
  - Substring replace on text [(Issue #8)](https://github.com/algenty/grafana-flowcharting/issues/8)
  - Editor object not found Exception [(Issue #1)](https://github.com/algenty/grafana-flowcharting/issues/1)
  - Original Link [(Issue #9)](https://github.com/algenty/grafana-flowcharting/issues/9)
  - Fixed Change the colors [(Issue #14)](https://github.com/algenty/grafana-flowcharting/issues/14)
  - Fixed Unit [(Issue #12)](https://github.com/algenty/grafana-flowcharting/issues/12)

## [[0.2.5]](https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.2.5.zip) - 2019-04-19
### Added
  - Mapping Helper for select object with mouse  
  
### Fixed
  - Substring replace on text [(Issue #8)](https://github.com/algenty/grafana-flowcharting/issues/8)
  - Editor object not found Exception [(Issue #1)](https://github.com/algenty/grafana-flowcharting/issues/1)

## [0.2.0] - 2019-03-18
### Added
  - Display graph through xml definition
  - Calibrate display (scale, center, background)
  - Inspect tab to test states and shape from graph.
  - Mapping values and colors (use stroke in color options for arrows instead fill)
  - String type added with range or value mapping.
  - Date type added
  - multi rules with expand/collapes for better display, possibility to reorg rules

## [0.1.0] - 2019-09-02
### Added
  - Display graph with mxgraph libs
  - Inspect tab to explore object in graph and preview colors

# Annex
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
