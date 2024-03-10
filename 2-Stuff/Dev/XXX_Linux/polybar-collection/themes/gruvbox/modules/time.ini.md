```
[module/time]
type = internal/date
interval = 1

time = "%H:%M"
time-alt = "%a, %b %d %H:%M:%S"

format = %{T9}%{T-} <label>
format-background = ${colors.bg-darker}
format-foreground = ${colors.bg-purple}
format-padding = 1
label = %{T2}%time%%{T-}
