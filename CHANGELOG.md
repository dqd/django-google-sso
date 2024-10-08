# Changelog

<!--next-version-placeholder-->

## v7.1.0 (2024-09-17)

### Feature

* Add new option GOOGLE_SSO_SHOW_FAILED_LOGIN_MESSAGE ([`e53accb`](https://github.com/megalus/django-google-sso/commit/e53accba4b3bb9046bbeb68aa26f23d345091c38))

## v7.0.0 (2024-08-29)

### Feature

* Remove support for Django 4.1 and add support to 5.1 ([`6e7573a`](https://github.com/megalus/django-google-sso/commit/6e7573a0acee58e9bdcd13ac60c389435dc314ba))

### Breaking

* Remove support for Django 4.1 and add support to 5.1 ([`6e7573a`](https://github.com/megalus/django-google-sso/commit/6e7573a0acee58e9bdcd13ac60c389435dc314ba))

### Documentation

* Small fixes ([`5219a90`](https://github.com/megalus/django-google-sso/commit/5219a90717f3700c93b116b4285260d9a8a0e5d4))

## v6.5.0 (2024-08-29)

### Feature

* Add `GOOGLE_SSO_PRE_VALIDATE_CALLBACK` option. ([`8163b93`](https://github.com/megalus/django-google-sso/commit/8163b93cf8950a255daaea764c87d1c98237eab4))

### Documentation

* Update settings.md ([`d0f3073`](https://github.com/megalus/django-google-sso/commit/d0f3073dae2117ccd935f4083a3decf039a85db1))

## v6.4.0 (2024-08-13)

### Feature

* Add new option GOOGLE_SSO_SAVE_BASIC_GOOGLE_INFO. ([`6a5a4d4`](https://github.com/megalus/django-google-sso/commit/6a5a4d4d90ab953c25b52058a4466702e59e65a6))

### Documentation

* Update Django version numbers to match implementation ([`a732f9d`](https://github.com/megalus/django-google-sso/commit/a732f9dc97794699249d3ab944d6e36b8a633f75))
* Update settings.md with current logo path ([`fa85eb8`](https://github.com/megalus/django-google-sso/commit/fa85eb8edd2f58959d291a06acf40326aa80a5e1))

## v6.3.0 (2024-07-31)

### Feature

* Add option to add all created users as staff ([`1a7b3ab`](https://github.com/megalus/django-google-sso/commit/1a7b3abc787126679db2bcc005ed45aac16381a9))

## v6.2.1 (2024-06-07)

### Fix

* Add support to Django USERNAME_FIELD ([`b62f560`](https://github.com/megalus/django-google-sso/commit/b62f560255b4662c2816b9d8b5a3b6b12eb73762))

## v6.2.0 (2024-04-23)

### Feature

* Add more control on messaging ([`c718030`](https://github.com/megalus/django-google-sso/commit/c7180305e05b6d146e6369e4635cebee9de17a57))

## v6.1.1 (2024-04-09)

### Fix

* Add token in request before call pre-create callback ([`2bf6467`](https://github.com/megalus/django-google-sso/commit/2bf6467c948ded6fc98df1e0d07ec84d4a9ffa0c))

## v6.1.0 (2024-04-09)

### Feature

* Add support to custom attributes in User model before creation. ([`cc9ad6a`](https://github.com/megalus/django-google-sso/commit/cc9ad6a6dc5263f6c9efd139102bd9070962d97a))

## v6.0.2 (2024-03-14)

### Fix

* Error when field `locale` was not available on Google API response. ([`646d986`](https://github.com/megalus/django-google-sso/commit/646d986d609aba7acc4f0df0ea0f6136a4fe7747))

## v6.0.1 (2024-03-12)

### Fix

* Bump version ([`59907fd`](https://github.com/megalus/django-google-sso/commit/59907fdb0234e73ffb498b7af5ebce3e36055c94))

## v6.0.0 (2024-03-12)

### Feature

* Add basic support to custom login templates. ([`75d979f`](https://github.com/megalus/django-google-sso/commit/75d979f2999dc77665aeb6cec64bd2c9c8a7c16d))

### Breaking

* Add basic support to custom login templates. ([`75d979f`](https://github.com/megalus/django-google-sso/commit/75d979f2999dc77665aeb6cec64bd2c9c8a7c16d))

### Documentation

* Better Stela use. ([`f34152f`](https://github.com/megalus/django-google-sso/commit/f34152ffde5a9eb1eb31a3983e1eba6e840838a0))

## v5.0.0 (2023-12-20)

### Feature

* New version ([`dc3560c`](https://github.com/megalus/django-google-sso/commit/dc3560c12398037f289dc1e8b08d4c8d40b7577a))

### Breaking

* * Remove Django 4.1 support * Add Django 5.0 support * Fix `SSO_USE_ALTERNATE_W003` bug * Fix several CSS issues with custom logo images * Update docs ([`dc3560c`](https://github.com/megalus/django-google-sso/commit/dc3560c12398037f289dc1e8b08d4c8d40b7577a))

## v4.0.0 (2023-11-23)

### Feature

* V4.0 ([`7212d2c`](https://github.com/megalus/django-google-sso/commit/7212d2c30a25710a507ed26e5640284bd8e87486))

### Breaking

* New changes: ([`7212d2c`](https://github.com/megalus/django-google-sso/commit/7212d2c30a25710a507ed26e5640284bd8e87486))

## v3.3.0 (2023-09-27)

### Feature

* Add GOOGLE_SSO_SHOW_FORM_ON_ADMIN_PAGE option. ([`efc33cd`](https://github.com/megalus/django-google-sso/commit/efc33cd418e3a89044687c40788d195abc4a38a8))

### Documentation

* Update example in docs ([`0db95f8`](https://github.com/megalus/django-google-sso/commit/0db95f8388329fc7937b1e10299c74fb7ba2960a))
* Better docs ([`2b3e3cb`](https://github.com/megalus/django-google-sso/commit/2b3e3cb3e72a9e6f4ec2b3a03660439b8a83139d))

## v3.2.0 (2023-09-19)

### Feature

* Add GOOGLE_SSO_ALWAYS_UPDATE_USER_DATA option ([`a106fcf`](https://github.com/megalus/django-google-sso/commit/a106fcf166b1463ddf159112ffa0d43ee999868f))

### Documentation

* Update example code in admin.md ([`4c38551`](https://github.com/megalus/django-google-sso/commit/4c38551647b45ff55872929230ac8c8697bab137))

## v3.1.0 (2023-08-16)

### Feature

* Add option to save access token ([`cd23c76`](https://github.com/megalus/django-google-sso/commit/cd23c76010a589e0bbe56e4bbab673668394e378))
* Add new configuration parameters and fix bugs ([`3b26037`](https://github.com/megalus/django-google-sso/commit/3b26037c1ebe549d10b4a25533d5ed72ad4e4c99))

## v3.0.0 (2023-04-19)
### Feature
* Version 3.0 ([`24bfb2e`](https://github.com/megalus/django-google-sso/commit/24bfb2e5849f3a637de68193506c3a943fcdbba7))

### Breaking
*  ([`24bfb2e`](https://github.com/megalus/django-google-sso/commit/24bfb2e5849f3a637de68193506c3a943fcdbba7))

### Documentation
* Fix typo ([`08c782d`](https://github.com/megalus/django-google-sso/commit/08c782df65519afac67d4662f568b3b3841b26c2))
* Update docs ([`a2ef5b7`](https://github.com/megalus/django-google-sso/commit/a2ef5b7026a84e971b6a1b1bf3544e53c7bf60e5))

## v2.5.0 (2023-04-05)
### Feature
* Update to Django 4.2 ([`677a5da`](https://github.com/megalus/django-google-sso/commit/677a5da8c4d0815595e4aaa72c363f8feb409a93))

### Documentation
* Update Stela example ([`6ff6676`](https://github.com/megalus/django-google-sso/commit/6ff6676b04729ef8d2687ee7f54bd31e68cba3a0))
* Improve documentation ([`131f1b1`](https://github.com/megalus/django-google-sso/commit/131f1b10a1398cc17a8eec95feb571de3cf6a0c8))

## v2.4.1 (2023-02-25)
### Fix
* UserManager error when GOOGLE_SSO_AUTO_CREATE_USERS is set to False ([`4451c6b`](https://github.com/chrismaille/django-google-sso/commit/4451c6bf228e29cba14b11fd6ee17d9f2089cefd))
* **docs/how.md:** Add missing S with GOOGLE_SSO_AUTO_CREATE_USERS ([`3e9b661`](https://github.com/chrismaille/django-google-sso/commit/3e9b661eaec4693541b92f85de65129f18bc3fe2))

## v2.4.0 (2023-01-23)
### Feature
* Add GOOGLE_SSO_PRE_LOGIN_CALLBACK feature ([`44ade37`](https://github.com/chrismaille/django-google-sso/commit/44ade37ce4f65a530562da4edbdc4c5d122d9f85))

## v2.3.1 (2023-01-18)
### Fix
* Small fixes ([`1ec44cc`](https://github.com/chrismaille/django-google-sso/commit/1ec44cc5f6080e8de67a0548b3af647ba96cc262))

## v2.3.0 (2022-10-28)
### Feature
* Release 2.3.0 ([`8ef3b04`](https://github.com/chrismaille/django-google-sso/commit/8ef3b04e2c096338c4b92126ebbf4f6cfac0d208))
* Add new settings option GOOGLE_SSO_AUTHENTICATION_BACKEND ([`4212782`](https://github.com/chrismaille/django-google-sso/commit/4212782eae4c1400e1d9634b79df83f4a5d36f3d))

## v2.2.0 (2022-09-06)
### Feature
* Make Sites Framework optional ([`e5a3839`](https://github.com/chrismaille/django-google-sso/commit/e5a38395b68ca4614b67cc5868c5adfd2a504f82))

## v2.1.0 (2022-09-02)
### Feature
* Add new settings option GOOGLE_SSO_CALLBACK_DOMAIN ([`4b49059`](https://github.com/chrismaille/django-google-sso/commit/4b490596a0e2efc47f3067628bb939d832da5ae5))

## v2.0.0 (2022-02-23)
### Feature
* Add django 4 support ([`dcb5f9f`](https://github.com/chrismaille/django-google-sso/commit/dcb5f9ff2329e54f38985cfb2eb1c0edd06ebf5a))

### Breaking
* update tests and example app  ([`dcb5f9f`](https://github.com/chrismaille/django-google-sso/commit/dcb5f9ff2329e54f38985cfb2eb1c0edd06ebf5a))

## v1.0.2 (2022-02-23)
### Fix
* Change license to MIT ([`750f979`](https://github.com/chrismaille/django-google-sso/commit/750f9791dcc7057359da08b69774515b63a3578d))

## v1.0.1 (2021-11-23)
### Fix
* Update Django Classifiers ([`17664cb`](https://github.com/chrismaille/django-google-sso/commit/17664cb89430f2be730b859a3d5926acb708300c))

### Documentation
* Add `login_required` use example and add Django Classifiers ([`fccc7b6`](https://github.com/chrismaille/django-google-sso/commit/fccc7b62174a2898e93a0ad483ffe014884b538c))
* Update README.md ([`c2e6c3b`](https://github.com/chrismaille/django-google-sso/commit/c2e6c3b17388f9ac7d5442f3d780cc2859071afd))

## v1.0.0 (2021-11-22)
### Feature
* First Release ([`54d979f`](https://github.com/chrismaille/django-google-sso/commit/54d979f06c76f6985483d642823f85c006776b19))

### Breaking
* This is version 1.0. To find additional information please check README.md file.  ([`54d979f`](https://github.com/chrismaille/django-google-sso/commit/54d979f06c76f6985483d642823f85c006776b19))

## v0.2.1 (2021-11-20)
### Fix
* Unit test ([`220920c`](https://github.com/chrismaille/django-google-sso/commit/220920cef5913bd24e78fe4da379b66b037078df))

## v0.2.0 (2021-11-20)
### Feature
* Add alpha version ([`98c78e5`](https://github.com/chrismaille/django-google-sso/commit/98c78e589016948f352c67849e36d937c455456e))
