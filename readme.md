What is this?
=

This is just set of useful functions which are more or less trivial.
Most of them was written for CleverStyle CMS, but I hope, they might be useful for others.

Requirements:
=

* PHP 5.5+

How to use?
=

Include upf.php into your project manually or add dependency on `nazar-pc/upf` to your project's `composer.json`:

```json
{
    "require": {
        "nazar-pc/upf": "*"
    }
}
```

Any docs?
=

Functions have PHPDoc comments, just look inside.

Functions list:
=

* \_require ()
* \_include ()
* \_require_once ()
* \_include_once ()
* time_limit_pause ()
* get_files_list ()
* file_extension ()
* file_exists_with_extension()
* rmdir_recursive()
* null_byte_filter ()
* prepare_attr_value ()
* \_stripslashes ()
* \_addslashes ()
* \_trim ()
* \_ltrim ()
* \_rtrim ()
* \_substr ()
* \_mb_substr ()
* \_strtolower ()
* \_strtoupper ()
* \_mb_strtolower ()
* \_mb_strtoupper ()
* \_json_encode ()
* \_json_decode ()
* \_json_decode_nocomments ()
* file_put_json()
* file_get_json()
* file_get_json_nocomments()
* \_preg_match ()
* \_preg_replace ()
* ip2hex ()
* hex2ip ()
* password_check ()
* password_generate ()
* xor_string ()
* is_md5()
* is_array_assoc ()
* is_array_indexed ()
* array_flip_3d ()
* truncate ()
* find_links()
* path ()
* keywords ()
* description ()
* ob_wrapper ()
* mb_ucwords ()
* \_int ()
* \_float ()
* \_string ()
* \_array ()
