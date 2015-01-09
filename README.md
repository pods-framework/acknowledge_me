# acknowledge_me
WordPress plugin that shows contributors to a Github repo.

### Usage
To output as HTML, use `acknowledge_me_display( $owner, $repo, $header_text = false, $total = 100 )` where `$owner` is the user name or organization name for the repo, and `$repo` is the repo name. Optioanlly add some header text or change the limit for the number of contributors.

Example, show 50 contributors to `https://github.com/pods-framework/pods/` with `acknowledge_me_display( 'pods-framework', 'pods', 'Pods Is Braught To You By:', 50 );`

Or use shortcode `[acknowledge_me owner="pods-framework" repo="pods" header_text="Pods Is Braught To You By:" total="50"]`

### License, Copyright, etc.
Based on the code for the underscores.me site: https://github.com/Automattic/underscores.me/, which is copyright Automattic, hugobaeta, kovshenin and GPL licensed.

This plugin copyright 2015 Josh Pollock. Licensed under the terms of the GPL v2 or later.