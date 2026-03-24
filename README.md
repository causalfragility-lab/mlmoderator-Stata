# mlmoderator

Robustness diagnostics and visualization tools for cross-level 
interaction effects in multilevel models fitted with Stata's `mixed` command.

Requires Stata 14.1+

## Installation

### From GitHub
```stata
net install mlmoderator, ///
    from("https://raw.githubusercontent.com/causalfragility-lab/mlmoderator-Stata/main/") ///
    replace
```

### From SSC (once approved)
```stata
ssc install mlmoderator
```

## Commands

| Command | Purpose |
|---|---|
| `mlmcenter` | Grand-mean, group-mean, or within-between centering |
| `mlmprobe` | Simple slopes at selected moderator values |
| `mlmjn` | Johnson-Neyman interval (exact analytical solution) |
| `mlmplot` | Publication-ready interaction plot |
| `mlmsummary` | Consolidated moderation report |
| `mlmvdecomp` | Decompose slope variance into fixed vs random |
| `mlmsens` | ICC-shift robustness + leave-one-cluster-out diagnostics |

## Author
Subir Hait, Michigan State University
