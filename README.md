# Flickr Set Tag With Fancybox Support

Generates image galleries from a Flickr set and adds fancybox scripts.

Fork of [jekyll_flickr_set_tag](https://github.com/macjasp/jekyll_flickr_set_tag) project



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
api_key:       	''
	
No need to flickr username.

You must provide an API Key in order to query Flickr. It must be configured in _config.yml.