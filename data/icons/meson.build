# install app icons
scalable_dir = 'scalable/apps'
install_data(
  scalable_dir / f'@application_id@.svg',
  install_dir : datadir / 'icons/hicolor' / scalable_dir,
)

symbolic_dir = 'symbolic/apps'
install_data(
  symbolic_dir / f'@rdnn_app_name@-symbolic.svg',

  install_dir : datadir / 'icons/hicolor' / symbolic_dir,
  rename      : f'@application_id@-symbolic.svg',
)
