# refs/tags/android-7.1.2_r36

## Apply all patches

- Copy needed ASB folder to your local Android source
- Apply all changes

```
repo forall -c "git am *.patch"
```

- Now delete all local patchfiles again

```
repo forall -c "rm -rf *.patch"
```

- Add the next ASB folder and start from beginning


### 2018

- https://review.lineageos.org/#/q/topic:n_asb_01-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_02-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_03-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_04-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_05-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_06-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_07-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_08-2018+(status:open+OR+status:merged)
- https://review.lineageos.org/#/q/topic:n_asb_09-2018+(status:open+OR+status:merged)
