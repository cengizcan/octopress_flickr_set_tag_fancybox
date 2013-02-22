# Flickr Set Tag

Generates image galleries from a Flickr set.

Usage:

    {% flickr_set flickr_set_id %}

Example:

    {% flickr_set 72157625102245887 %}

Default Configuration (override in _config.yml):

    flickr_set:
      gallery_tag:   'p'
      gallery_class: 'gallery'
      a_href:        nil
      a_target:      '_blank'
      image_rel:     ''
      image_size:    's'
      per_page:      '500'
      user:          ''
      api_key:       ''

You need your flickr username as the thumbnails automatically link to the full flickr page within your photostream.

a_href is defunct and will remove in the next version.

You must provide an API Key in order to query Flickr. It must be configured in _config.yml.