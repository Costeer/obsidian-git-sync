```
[module/date]
type = internal/date
interval = 1

date = %d.%m.

format = %{T9}%{T-} <label>
format-background = ${colors.bg-dim}
format-foreground = ${colors.yellow}
format-padding = 0.5
label = %{T2}%date%%{T-}
