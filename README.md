<h2>org-bullets mode</h2>
Show org-mode bullets as UTF-8 characters.

![screenshot](https://github.com/sabof/org-bullets/raw/master/screenshot.png)

<h4>Installation</h4>
<h3>Manual</h3>
Copy the file somewhere in your load-path, then add to your .emacs:

    (require 'org-bullets)
    (add-hook 'org-mode-hook (lambda () (org-bullets-mode 1)))

select, do [M-x eval-region]. The *s will be replaced with utf-8 bullets next time you open an org file
<h3>Through MELPA and package.el</h3>
After downloading the package, do [M-x customize-variable RET org-mode-hook],
check the org-bullets-mode checkbox. [C-x C-s]. That's it.