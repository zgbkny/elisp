;;;;; 自动启动smex
(require 'smex) ; Not needed if you use package.el
(smex-initialize) ; Can be omitted. This might cause a (minimal) delay
                  ; when Smex is auto-initialized on its first run.
(global-set-key (kbd "M-x") 'smex)
(global-set-key (kbd "M-X") 'smex-major-mode-commands)
;; This is your old M-x.
(global-set-key (kbd "C-c C-c M-x") 'execute-extended-command)

;;;;;加载配色主题
(add-to-list 'custom-theme-load-path "~/.emacs.d/elisp/themes/")
(load-theme 'molokai t)
(custom-set-variables
 ;; custom-set-variables was added by Custom.
 ;; If you edit it by hand, you could mess it up, so be careful.
 ;; Your init file should contain only one such instance.
 ;; If there is more than one, they won't work right.
 '(custom-safe-themes
   (quote
    ("c3c0a3702e1d6c0373a0f6a557788dfd49ec9e66e753fb24493579859c8e95ab" default))))
(custom-set-faces
 ;; custom-set-faces was added by Custom.
 ;; If you edit it by hand, you could mess it up, so be careful.
 ;; Your init file should contain only one such instance.
 ;; If there is more than one, they won't work right.
 )

;;;;;设置tab
(setq-default indent-tabs-mode nil)
(setq default-tab-width 4)

;;;;;显示括号匹配 
(show-paren-mode t)
(setq show-paren-style 'parentheses)

;;;;;显示列号
(setq column-number-mode t)
(setq line-number-mode t)

;;;;;显示时间，格式如下
(display-time-mode 1) 
(setq display-time-24hr-format t) 
(setq display-time-day-and-date t) 
(transient-mark-mode t)

;;;;;在标题栏提示你目前在什么位置
(setq frame-title-format "wangwei@%b")

;;;;; 设置字体
;;;;; 方法为: emacs->options->Set Default Font->"M-x describe-font"查看当前使用的字体名称、字体大小
(set-default-font " -bitstream-Courier 10 Pitch-normal-normal-normal-*-16-*-*-*-m-0-iso10646-1")
