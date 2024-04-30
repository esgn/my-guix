# my-guix

Test channel 

Use this repo as a [channel](https://guix.gnu.org/manual/en/html_node/Channels.html) add the following lines in the `~/.config/guix/channels.scm` file :

``` scheme
(append (list (channel
                (name 'esgn-guix-packages)
                (url "https://github.com/esgn/my-guix.git")
		(branch "main")))
        %default-channels)
```
