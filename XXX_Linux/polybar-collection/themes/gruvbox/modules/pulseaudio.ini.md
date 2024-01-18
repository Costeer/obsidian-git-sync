[module/pulseaudio]
type = internal/pulseaudio
use-ui-max = false

format-volume = <label-volume>
format-volume-padding = 0.5
format-volume-prefix = %{T5}%{T-}
format-volume-prefix-foreground = ${colors.orange}
format-volume-prefix-background = ${colors.bg-darker}
label-volume = %{T2}%percentage%%%{T-}
label-volume-foreground = ${colors.fg}
label-volume-background = ${colors.bg-darker}
label-volume-padding = 1

format-muted = <label-muted>
format-muted-padding = 0.5
format-muted-prefix = %{T5}%{T-}
format-muted-prefix-foreground = ${colors.red}
format-muted-prefix-background = ${colors.bg-darker}
label-muted = %{T2}%percentage%%%{T-}
label-muted-foreground = ${colors.fg}
label-muted-background = ${colors.bg-darker}
label-muted-padding = 1

click-right = pavucontrol&
