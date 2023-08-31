function show_loggedin_function( $atts ) {

global $current_user, $user_login;
      get_currentuserinfo();
add_filter('widget_text', 'do_shortcode');
if ($user_login) 
return 'Welcome <a href="https://domain.com/account/">' . $current_user->display_name . '</a> !';
else
return '<a href="https://domain.com/account/">Login</a>';

}
add_shortcode( 'show_loggedin_as', 'show_loggedin_function' );
