---
title: "Geometry Section"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
f1_keywords:
- Vis_DSS.chm2055
 
ms.localizationpriority: medium
ms.assetid: 75601a1e-6b1a-27ee-a2bd-69e569315982
description: "Contains rows that list the coordinates of the vertices for the lines and arcs that make up the shape."
---

# Geometry Section

Contains rows that list the coordinates of the vertices for the lines and arcs that make up the shape. 
  
The geometry of a shape can be expressed in multiple **Geometry** sections. Multiple paths can be useful when multiple paths have different properties (e.g. [image clipping](clippingpath-cell-foreign-image-info-section.md) paths). 
  
## Remarks

The **Geometry** section contains the following row types. For details, see the row topics. 
  
|Row|Description|
|:-----|:-----|
|[MoveTo](moveto-row-geometry-section.md) <br/> |Move to a coordinate. |
|[LineTo](lineto-row-geometry-section.md) <br/> |Draw a line to a coordinate. |
|[ArcTo](arcto-row-geometry-section.md) <br/> |Draw a circular arc to a coordinate. |
|[EllipticalArcTo](ellipticalarcto-row-geometry-section.md) <br/> |Draw an elliptical arc to a coordinate. |
|[PolylineTo](polylineto-row-geometry-section.md) <br/> |Draw a polyline, or consecutive lines, to a coordinate. |
|[NURBSTo](nurbsto-row-geometry-section.md) <br/> |Draw a non-uniform rational B-spline (NURBS) to a coordinate. |
|[SplineStart](splinestart-row-geometry-section.md) <br/> |Start a spline. |
|[SplineKnot](splineknot-row-geometry-section.md) <br/> |Draw a spline segment to a knot coordinate. |
|[InfiniteLine](infiniteline-row-geometry-section.md) <br/> |Draw an infinite line from one coordinate to another. |
|[Ellipse](ellipse-row-geometry-section.md) <br/> |Draw an ellipse from a center coordinate and a major/minor axis. |
|[RelCubBezTo](relcubbezto-row-geometry-section.md) <br/> |Draw a cubic Bezier curve relative to the width and height of the shape. |
|[RelEllipticalArcTo](relellipticalarcto-row-geometry-section.md) <br/> |Draw an elliptical arc to a coordinate relative to the height and width of the shape. |
|[RelLineTo](rellineto-row-geometry-section.md) <br/> |Draw a line to a coordinate relative the height and width of a shape. |
|[RelMoveTo](relmoveto-row-geometry-section.md) <br/> |Move to a coordinate relative to the width and height of the shape. |
|[RelQuadBezTo](relquadbezto-row-geometry-section.md) <br/> |Draws a quadratic Bezier curve relative to the width and height of the shape. |
   
To change a row type in this section, right-click the row, and then click **Change Row Type** on the shortcut menu. 
  

