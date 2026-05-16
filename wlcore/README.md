# WaysCore

### The compositor and language land for wayland

##### v.0.0.0.dev0-pre1

## Project structure

The directories are sorted by their functional meaning for the ways project:

* `wlx`: The window space that makes wayland compositing program context UI and desktops
* `wlr`: The rendering engine basing on cairo and `wlx`. It also supports openGL vector graphics and
            movement-in-picture (see folder `wlrgl`).
* `wlrgl`: The rendering engine for vector graphics, 3D effects, shaders and movement-in-pictures.
* `wlroot`: The meta-layer for wayland compositing pictures and shader/vector tensors.
* `wlenv`: The environment space for all variables used in ways.
* `wlful`: Wayland ReSTful layer, for setting up and puzzle-tile togeter what you need for your
            UI graphics or commiting your 2D or 3D-pictures to embedded or in-house/sub-networked screen devices
* `wlsc`: The screen library for setting up pictures on screen.
* `wljh`: The wayland jade/html rendering and templating engine.
* `wlcr`: The wayland cairo backend.
* `wlnk`: The wayland 3D compositing backend.
* `wlu`: The wayland user-space API.
* `wln`: The wayland notifier framework API.
* `wle`: The wayland event framework API.
* `wlcg`: The wayland CGI compositor.
* `wljs`: JavaScript/TypeScript for your desktop GUI.
* `ways`: The libraries API.
* `meon`: The compiler utilities for building projectes with meon, a combination of meson, cmake, tsc and rake. It makes eoniful actress actions for building GUI projects or desktops basing on simple markup languages like html, markdown and css.
* `wllang`: Make `wlroot`, `wlful` and `wlu` available to `GoLang` and language independent with `gRPC`.
* `wlquick`: The wlquick (markup) language bases on a ObjC-prototyping dialect thus implemented with `RubyWL`, `json-Restful`, `C++`, `TypeScript` and `oimt`, a open image messaging tensor format. `wllang` then resembles the ObjC-like `*.h`/`*.och` file in a common `*.lib` with gRPC with a layer making it available to the languages accompanying `gRPC` and links everinthing with `meon` for waylang.

Each directory contains an own readme describing what the surproject is doing, how to use and how to build it.
