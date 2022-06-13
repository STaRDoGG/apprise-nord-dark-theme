# Nord Dark Theme (Blue) for Apprise

Dark Theme for [Apprise](https://github.com/caronc/apprise-api) Based on the Nord Palette 


# Usage

This was created to use with the Apprise container (*i.e. I havent taken any time out to create a special one for browser extensions like Stylish*) so the easiest way to use the theme is to mount the `.css` files:

1. Download the 2 `.css` files to some local folder:
- [materialize.min.css](https://github.com/STaRDoGG/apprise-nord-dark-theme/blob/main/minified/materialize.min.css "materialize.min.css")
- [highlight.min.css](https://github.com/STaRDoGG/apprise-nord-dark-theme/blob/main/minified/highlight.min.css "highlight.min.css")
2. Mount them to your Apprise container, paying attention to the container paths in the example below:

**Example how to mount them using Docker Compose:**

    volumes:
      - '/opt/docker/configs/apprise/css/highlight.min.css:/usr/share/nginx/html/s/css/highlight.min.css:ro'
      - '/opt/docker/configs/apprise/css/materialize.min.css:/usr/share/nginx/html/s/css/materialize.min.css:ro'

3. Restart the Apprise container and refresh the webpage (make sure to empty your browser cache as well): **Ctrl+F5**
# Screenshots

**_Note_**: These are the original screenshots upon initial theme release; as such, they may not always show the absolute latest changes and tweaks (if any).


![Overview](https://github.com/STaRDoGG/apprise-nord-dark-theme/blob/9bf695c4afeae24dffbef57cbc494e9545b48f60/screenshots/apprise-notifications-nord-theme-overview-j-scott-elblein.jpg?raw=true)

![Configuration](https://raw.githubusercontent.com/STaRDoGG/apprise-nord-dark-theme/main/screenshots/apprise-notifications-nord-theme-configuration-j-scott-elblein.jpg)

![Notifications](https://raw.githubusercontent.com/STaRDoGG/apprise-nord-dark-theme/main/screenshots/apprise-notifications-nord-theme-notifications-0-j-scott-elblein.jpg)

![Notifications Popop](https://raw.githubusercontent.com/STaRDoGG/apprise-nord-dark-theme/main/screenshots/apprise-notifications-nord-theme-notifications-j-scott-elblein.jpg)

![Notification Result](https://raw.githubusercontent.com/STaRDoGG/apprise-nord-dark-theme/main/screenshots/apprise-notifications-nord-theme-message-result-j-scott-elblein.jpg)
