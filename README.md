# BlueStrap - A simple Bootstrap theme

# Build

```
bower install
mkdir css
recess --compile bootstrap.less > css/bootstrap.css
recess --compress bootstrap.less > css/bootstrap.min.css
recess --compile components/bootstrap/less/responsive.less > css/responsive.css
recess --compress components/bootstrap/less/responsive.less > css/responsive.min.css
# copy fonts
cp components/font-awesome/font . -R
```
