# Flickr Set Tag with fancybox support

Fork of https://github.com/macjasp/jekyll_flickr_set_tag

Generates image galleries from a Flickr set.

Usage:

    {% flickr_set flickr_set_id %}

Example:

    {% flickr_set 72157625102245887 %}

Default Configuration (override in _config.yml):

flickr_set:
gallery_tag:	'p'
gallery_class:	'gallery'
effect: 		'elastic' # 'fade', 'elastic'
openCloseSpeed: '250'
nextPrevSpeed: 	'250'
loop: 			'true'
image_size:    	'b'
thumb_size:    	'q'
per_page:      	'500'
user:          	''
api_key:       	''

You need your flickr username as the thumbnails automatically link to the full flickr page within your photostream.

a_href is defunct and will remove in the next version.

You must provide an API Key in order to query Flickr. It must be configured in _config.yml.