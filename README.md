<div align="center" style = "box-pack: start;">
  </br>
  <img width = 300 src="https://github.com/ChifiSource/image_dump/blob/main/ipyjl/logo.png" >
  
  
  [![version](https://juliahub.com/docs/Lathe/version.svg)](https://juliahub.com/ui/Packages/Lathe/6rMNJ)
[![deps](https://juliahub.com/docs/Lathe/deps.svg)](https://juliahub.com/ui/Packages/Lathe/6rMNJ?t=2)
[![pkgeval](https://juliahub.com/docs/Lathe/pkgeval.svg)](https://juliahub.com/ui/Packages/Lathe/6rMNJ)
  </br>
  </br>
  <h1>IPy.jl</h1>
  </div>

**IPy.jl** is a unity of all notebook file formats into Julia. This allows for quick translation between Julia code and different notebook types. These formats include
- regular .jl Julia files./Olive.jl files.
- .ipynb jupyter notebook files.
- Pluto .jl files.
These files can all be read and exported to via the Cells data structure and a few methods. 
### Adding
```julia
julia> ]
pkg> add https://github.com/emmettgb/IpyJL.jl.git
```
### Usage
[For more information; see the Documentation!]()
The usage of this module is pretty simple, there are three methods that need to be payed attention to in this library.
```julia
save(cells::Cells, URI::String)
open(URI::String)
```
### Module Composition
- [**IPy**]() - High-level API
- [IPyRW]() - Reading of cells into **Cell** and writing of **Cell** to file output.
- [IPyCells]() - Provides **Cell** structure.
#### odddata
##### core
- [OddStructures.jl]()
- [OddFrames.jl]()
- [OdDb.jl]()
##### formats
- **IPy.jl**
