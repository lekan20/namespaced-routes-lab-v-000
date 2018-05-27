[x] Create a `Preference` model that will store preferences for the app. It will need
   to have fields for:
   * Song sort order (e.g. `"ASC"` or `"DESC"`). This will be used to control the default sort order on the `/songs` page.
   * Artist sort order. This will be used to control the default sort order on the `/artists` page.
   * Allowing creation of new songs. Used to control the ability to add new songs to the system.
   * Allowing creation of new artists. Used to control the ability to add new artists to the system.
[x] Create a `PreferencesController`, routes, and views to manage the preferences. Do this under an `Admin` module to separate it from the standard user functionality.
[] Update the artists and songs `index` pages to order by `name` according to each preference.
[] Update the `songs#new` and `artists#new` actions to check that creating new songs or artists is enabled, and redirect to `/songs` and `/artists`, respectively, if that preference is disabled.
[] Make sure tests pass.



[x] spec/model/preferences
[x] spec/controller/preferences
[x] spec/views/songs/index
[x] spec/views/songs/song
[] spec/model/song
[] spec/controller
[] spec/views
