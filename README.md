# Emacs Theme Switcher

A simple program that switches betweentwo themes at the desired time

## How to use it

The config is quite simple, you just need to set both of the themes and the hours when you want the theme to switch  

`light-theme` is the day theme  
`dark-theme` is the night theme  
`morning-hour` is the hour of the switch in the morning  
`evening-hour` is the hour of the switch in the evening  


``` emacs-lisp
;; Set the light and dark theme
(setq light-theme 'spacemacs-light)
(setq dark-theme 'spacemacs-dark)

;; Set the hour when you want the theme to switch
(setq morning-hour 07)
(setq evening-hour 18)
```

## Todos

-[ ] Make the hour more precise
