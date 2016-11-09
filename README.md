# MittagLeffler

*Mittag-Leffler function*

[![Build Status](https://travis-ci.org/jlapeyre/MittagLeffler.jl.svg?branch=master)](https://travis-ci.org/jlapeyre/MittagLeffler.jl)

[![Coverage Status](https://coveralls.io/repos/jlapeyre/MittagLeffler.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/jlapeyre/MittagLeffler.jl?branch=master)

[![codecov.io](http://codecov.io/github/jlapeyre/MittagLeffler.jl/coverage.svg?branch=master)](http://codecov.io/github/jlapeyre/MittagLeffler.jl?branch=master)


```julia
mittlefferr(α,β,z,ρ)   # evaluate Mittag-Leffler function with tolerance ρ
mittlefferr(α,z,ρ)     # mittlefferr(α,1,z,ρ)

mittleff(α,β,z)   # evaluate Mittag-Leffler function with tolerance eps()
mittleff(α,z)     # mittleff(α,1,z)
```

### Reference

Rudolfo Gorenflo, Joulia Loutchko and Yuri Loutchko, *Computation of the Mittag-Leffler function and its derivative*,  Fract. Calc. Appl. Anal, **(2002)**
