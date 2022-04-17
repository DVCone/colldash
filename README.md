![preview.jpg](https://github.com/DVCone/colldash/blob/main/preview.png)

# CollDash

Hi, Thank you for Comming ;D

This is landing Page UI design I implemented with Flutter Framework about Collage Courses Dashboard App and I call it "CollDash".

I think this is a simple project because just a one Landing Page but also I got some obstacles about image assets, I'll explain to you in "What I learn from this project" Section.

the main lesson in this project it's about using Card widget in flutter. so, You can practice too in this project with your own and develope this project into newest framework version, feel free to use my code.

## System Requirement :
- Dart v.2.16
- Flutter v.2.10

## Dependency Requirement :
- flutter_svg v.1.0.3

note: this dependency is use for import SVG assets from embeded URL if you use it (in my case, I don't use it).

## What I learn from this project :
1. I learn how to use `card` widget using `GridView.count`. <br/> [see on `home_screen.dart` at `Card List Section`]

2. I learn how to embed SVG image with `SvgPicture.network` widget from `flutter_svg` dependency. <br/> [see on `home_screen.dart` at `Personal Data Card`]

3. I learn how to make header Image in background. <br/> [see on `home_screen.dart` at `Background Image on Header`]

4. I learn about `CircleAvatar` Radius even better. <br/>[see on `home_screen.dart` at `Profile Section`]

5. Originally the assets project is come from Flaticon CSS embeded Icon, but flaticon not support embeded SVG for free anymore. so, I trick it with download the PNG version of Icon with 64px Scale and put into the `assets/icons`. <br/> [see on `pubspec.yaml` at `assets: `]

If you want re-create and re-wrote this project, I hope you can find more what I can learn.

> See and Download my code on **[GitHub](https://github.com/DVCone/colldash)**.

## Credit :
I will credit all who's my Inspiration in this project bellow, so make sure you also check their profile later.

+ First Coded by Abdul Aziz Ahwan : [Watch Now](https://www.youtube.com/watch?v=IqFP7jY_enc).

+ Icons by Kiranshastry : [See Now](https://www.flaticon.com/packs/school-79/2).
