# Medusa - A modern CSS theme for Jellyfin
<img float="left" src=".github/images/Logo.png" alt="" width="80"/>

### Home
![](.github/images/Homescreen.jpg)

![](.github/images/Favourites.jpg)

![](.github/images/Sidemenu.jpg)

## Usage
Dashboard -> General -> Custom CSS code:
```
@import url("https://cdn.jsdelivr.net/gh/Arrow420/Medusa@main/Medusa.css");
```
Settings:
```
Settings -> Display -> Theme: Select 'Blue Radience'
Settings -> Display -> Theme: Tick 'Backdrops'
```

### Library
![](.github/images/Library_Thumbview.jpg)
![](.github/images/Library_Posterview.jpg)


### Details Page
![](.github/images/SeriesOverview.jpg)

![](.github/images/Season.jpg)

![](.github/images/Episode.jpg)

![](.github/images/MovieOverview.jpg)


### Dashboard
![](.github/images/Dashboard.jpg)


------------------------------
### My Custom Subtitle styling for Jellyfin Media Player
![](.github/images/Subtitles.jpg)
Paste into "Settings -> Client Settings -> Other - Manual MPV Configuration":
```
sub-font="Segoe UI Semibold"
sub-font-size=38
sub-color="#FFFFFF"
sub-border-size=1.2
sub-shadow-offset=0.2
sub-margin-x=180
sub-margin-y=42
sub-color="#FFFFFF"
sub-border-color="#000000"
sub-shadow-color="#000000"
sub-fix-timing=no
stretch-image-subs-to-screen=no
sub-filter-sdh=yes
sub-filter-sdh-harder=no
sub-filter-regex-enable=yes
sub-filter-jsre=opensubtitles|addic7ed|subscene|(English - US - SDH)|dreaMaker7|(sync.+?corrected by)|(www\.tvsubtitles\.net)
sub-use-margins=no
sub-gray=yes
```
