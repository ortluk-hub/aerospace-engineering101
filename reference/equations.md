# Equations and conventions
SI unless stated otherwise; upward positive in the elementary vertical model. These equations have different assumptions.

| Relation | Meaning | Assumptions / caution |
|---|---|---|
| W = mg | Weight | Local g approximated as 9.81 m/s² initially |
| F_net = ma | Translation | Use a consistent system and frame |
| a = (T − D − mg)/m | Vertical upward-flight acceleration | Thrust vertical; upward motion in still air |
| I = ∫ T dt | Total impulse, N·s | Area under thrust-time curve |
| T/W = T/(mg) | Thrust-to-weight ratio | State instantaneous or average thrust and which mass |
| A = πd²/4 | Circular reference area | Use the area convention of the drag model |
| D = ρ v_rel² C_D A / 2 | Drag magnitude | Relative air speed; direction opposes relative motion |
| q = ρ v_rel²/2 | Dynamic pressure | Not the same as drag force |
| SM = (x_CP − x_CG)/d | Static margin in calibres | Positions measured aft from nose; not complete dynamic stability |
| Δv = I_sp g₀ ln(m₀/m_f) | Ideal rocket equation | Constant effective exhaust speed; excludes gravity/drag losses |
| v_c = sqrt(μ/r) | Circular orbital speed | Two-body approximation; r from central body's centre |
| v_esc = sqrt(2μ/r) | Escape speed | Two-body idealization |

g₀ = 9.80665 m/s² is standard gravity used in the definition of specific impulse. It differs from an approximate local g. ln means natural logarithm. ∫ means accumulate continuously; dt is a small increment of time. d(v)/dt means rate of velocity change, not diameter. Symbol meanings depend on context.

A future no-drag coast calculation is conditional on burnout speed; it is not a substitute for modelling powered ascent. T/W alone cannot establish safe departure speed from a launch guide.
