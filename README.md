# W3L Moodle Plugins (Nexa 4 Moodle Plugins)

Plugins by **W3L Web Solutions** for Moodle 4.5.
 
## Contents
- [Nexa 4: Moodle Course Format](#nexa-4-moodle-course-format)
  - [About](#about)
  - [Features](#features)
  - [Requirements](#requirements)
  - [Installation](#installation)
    - [Way 1: Moodle Admin](#way-1-moodle-admin-recommended)
    - [Way 2: FTP/SFTP](#way-2-ftpsftp)
  - [Usage](#usage)
  - [Tip: for a better experience](#tip-for-a-better-experience)
  - [Supported languages](#supported-languages)
- [Nexa4: Moodle Theme](#nexa4-moodle-theme)
  - [About](#about-1)
  - [Features](#features-1)
  - [Requirements](#requirements-1)
  - [Installation](#installation-1)
    - [Way 1: Moodle Admin](#way-1-moodle-admin)
    - [Way 2: FTP/SFTP](#way-2-ftpsftp-1)
    - [Activate the theme](#activate-the-theme)
  - [Dark mode](#dark-mode)
  - [Tip: for a better experience](#tip-for-a-better-experience-1)
  - [Supported languages](#supported-languages-1)
- [License](#license)

# Nexa 4: Moodle Course Format

> Turn your Moodle course into a sleek lesson player with live progress tracking.

![Moodle 4.5](https://img.shields.io/badge/Moodle-4.5-orange) ![Version 2.1.0](https://img.shields.io/badge/version-2.1.0-blue) ![Stable](https://img.shields.io/badge/maturity-stable-brightgreen) ![License GPL v3](https://img.shields.io/badge/license-GPL%20v3-lightgrey)

## About

Nexa 4 transforms your Moodle course into a modern, distraction-free learning experience. Students see the current activity on the left, while the course content and their progress sit neatly on the right, so they always know where they are and what comes next.

Previous/Next navigation keeps learners moving through lessons, a progress bar shows completion at a glance, and a fullscreen mode puts the focus on the content.

It's built for Moodle 4.5, ships with English, Spanish, French and Brazilian Portuguese, and stores no personal data, so it's privacy-friendly. Install in minutes, switch it on per course, and give your students the polished, Netflix-style lesson flow they expect.

## Features

- **Lesson player layout:** the current activity on the left, content and progress on the right.
- **Progress tracking:** activity count and percentage complete.
- **Previous / Next navigation** between activities.
- **Fullscreen mode** for distraction-free learning.
- **Privacy-friendly:** no personal data is stored.
- **Multilingual:** English, Spanish, French and Brazilian Portuguese.

## Requirements

- Moodle 4.5

## Installation

### Way 1: Moodle Admin (recommended)

1. Log in to your Moodle site as an administrator.
2. Go to **Site Administration > Plugins > Install plugins**. This is the "Upload a plugin" screen.
3. Drag and drop the ZIP file `moodle_courseformat_nexa4.zip`, or choose it with the file picker.
4. Under **Plugin type**, leave it on "Course format" if Moodle doesn't detect it automatically.
5. Click **Install plugin from the ZIP file**.
6. Click **Continue** and confirm the plugin details on the validation screen.
7. Click **Upgrade Moodle database now** and finish by clicking **Continue**.

### Way 2: FTP/SFTP

1. Unzip the file on your computer. You'll get a folder named `nexa4`.
2. Connect to your server with an FTP/SFTP client such as FileZilla.
3. Upload the whole `nexa4` folder to `<your_moodle_folder>/course/format/`. The final path should be `<your_moodle_folder>/course/format/nexa4/`.
4. Log in to your Moodle site as an administrator. Moodle will detect the new plugin and open the installation page.
5. Click **Upgrade Moodle database now** and finish the setup by clicking **Continue**.

## Usage

1. Open the course you want to change.
2. Go to **Course > Settings**.
3. Open the **Course format** section.
4. In the **Format** dropdown, select **Nexa 4**.
5. Click **Save and display**.

## Tip: for a better experience

Add an **Administration** block to your course. With Nexa 4's focused layout, it keeps the course settings, participants, reports and other teacher tools one click away.

1. Open your course and turn on **Edit mode**.
2. Open the block drawer and click **Add a block**.
3. Select **Administration**.

## Supported languages

- English
- Spanish
- Portuguese (Brazil)
- French

# Nexa4: Moodle Theme

> A clean, modern Moodle theme with dark mode, built to impress learners and empower teachers.

![Moodle 4.5](https://img.shields.io/badge/Moodle-4.5-orange) ![Version 1.0](https://img.shields.io/badge/version-1.0-blue) ![Stable](https://img.shields.io/badge/maturity-stable-brightgreen) ![License GPL v3](https://img.shields.io/badge/license-GPL%20v3-lightgrey)

## About

Nexa4 gives your Moodle a smooth, polished experience that learners enjoy and teachers still control. Built on Boost, it keeps Moodle clean, safe and ready to grow, with all the power administrators and teachers rely on.

Enjoy a collapsible sidebar, a welcome banner, a searchable course gallery and a dark mode that each user can switch on or off to suit their own taste. Set your logo, colors, fonts and footer links in minutes, or build your own color scheme or import one from another Moodle.

Ideal for corporate training and selling online courses.

## Features

- **Collapsible sidebar** for clean, focused navigation.
- **Welcome banner** on the dashboard.
- **Searchable course gallery** so learners find courses fast.
- **Dark mode**, switched on or off by each user.
- **Easy branding:** logo, colors, fonts and footer links.
- **Custom color schemes:** build your own or import one from another Moodle.
- **Built on Boost**, keeping Moodle clean, safe and ready to grow.
- **Multilingual:** English, Spanish, Portuguese (Brazil) and French.

## Requirements

- Moodle 4.5

## Installation

### Way 1: Moodle Admin

1. Log in as administrator and go to **Site Administration > Plugins > Install plugins**.
2. Drop in `moodle_theme_nexa4.zip`, or choose it with the file picker.
3. Set **Plugin type** to **Theme** if Moodle doesn't detect it automatically.
4. Click **Install plugin from the ZIP file**, then **Continue**.
5. Click **Upgrade Moodle database now**, then **Continue**.

### Way 2: FTP/SFTP

1. Unzip the file. You'll get a folder named `nexa4`.
2. Upload it to `<your_moodle_folder>/theme/`. The final path is `<your_moodle_folder>/theme/nexa4/`.
3. Log in as administrator and click **Upgrade Moodle database now**.

### Activate the theme

Go to **Site Administration > Appearance > Themes > Theme selector**, choose **Nexa4** and save.

## Dark mode

Each user chooses the mode that suits them best. A toggle lets them switch between light and dark whenever they like, and Nexa4 remembers their choice.

## Tip: for a better experience

- Use the **Nexa 4 course format**.
- Install the recommended plugin **local/quicknote**. It lets users take notes about courses and content, and recall them later.

## Supported languages

- English
- Spanish
- Portuguese (Brazil)
- French

---

## License

Both plugins are released under the [GNU GPL v3 or later](http://www.gnu.org/copyleft/gpl.html).

Crafted by **[W3L Web Solutions](https://w3l.com.br)**.
