# raw-wine
Wine runners tested to work with StarCitizen

My runners should be as native wine as possible. 
It is always a wine-staging build, built in podman containers with the glibc from Ubuntu18.
Wine builds with lower glibc-version run on a much bigger scale of distributions.

Runners, wich are a native wine-staging, unmodified and working with SC, have (Staging) in their version string.
Runners wich need a modified wine-staging version, because a native wine can not run SC, have (rAWwINe) in their version string.
That way you can see quick, if the runner is modified or an original wine-staging.
Possible needed modifications are always posted in the release notes of each runner.

Check the **releases** for downloads:
https://github.com/rawfoxDE/raw-wine/releases
