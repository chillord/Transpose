# Icon font assets

Both WOFF2 files are subsets returned by Google Fonts for the icon selections
used in `src/theme/transpose.theme.scss`. They were downloaded on 2026-10-16;
the Google Fonts CSS asset versions were Material Icons `v145` and Material
Symbols `v377`.

- `material-icons-subset.woff2`: Material Icons, classic regular style, with
  the character subset required by the project's listed icon ligatures. The
  `text=` parameter selects characters, not semantic icon names.
- `material-symbols-outlined-subset.woff2`: Material Symbols Outlined variable
  font, axes `opsz 20..48`, `wght 100..700`, `FILL 0..1`, and `GRAD -50..200`,
  with the project icon selection from the `icon_names=...` request in the
  theme.

Exact Google Fonts CSS source requests used for the subsets:

- <https://fonts.googleapis.com/icon?family=Material+Icons&text=account_circle,add,arrow_back,arrow_downward,arrow_drop_down,arrow_forward,arrow_upward,auto_graph,bookmark,bookmark_border,bookmark_outline,brightness_auto,bug_report,cancel,check,chevron_right,close,content_copy,content_cut,dark_mode,delete,delete_outline,download,drag_indicator,edit,error,expand_less,expand_more,fast_forward,fast_rewind,help_outline,hourglass_top,light_mode,link,lock_reset,menu_book,more_vert,music_note,new_releases,pause,play_arrow,play_circle,power_settings_new,refresh,remove,remove_circle_outline,repeat,repeat_one,settings,skip_next,skip_previous,sort,tune,update,view_agenda,view_module,visibility_off,volume_down,volume_off,volume_up,zoom_in,zoom_out>
- <https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200&icon_names=arrow_range,audio_capture,collapse_content,dashboard_customize,edit,equalizer,expand_content,float_landscape_2,graphic_eq_off,grid_view,history_off,keyboard,laps,library_music,music_off,piano,reset_settings,restart_alt,save,share,view_list,view_sidebar>

Upstream source and license:

- Google Fonts CSS: <https://fonts.googleapis.com/icon?family=Material+Icons>
  and <https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined>
- Google Material Design Icons source: <https://github.com/google/material-design-icons>
- License: Apache License 2.0, reproduced in `LICENSE.txt` and available at
  <https://github.com/google/material-design-icons/blob/master/LICENSE>.
