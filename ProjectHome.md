Say you have a library written against `java.awt.Graphics(2d)` and other `java.awt` graphics related classes. A library to do plots or other things.

If you want to use this in GWT you would have to rewrite quite a bit. gwt-vectorgraphics provides you with a `GraphicsContext` and graphics support interfaces to rewrite your library against, so that you can either use `java.awt.Graphics2d` underneath, or some SVG/VML generated nodes for GWT.

Code: coming soon...