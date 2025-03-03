## yimmy theme

A simple two-line theme with support for terminals configured with Solarized
Dark colors.

    user@host ~/c/w/dir (branch *)
    >

![Screenshot](https://cloud.githubusercontent.com/assets/2502736/3245408/32c42cde-f172-11e3-8ba3-912191222a11.png)

### Characteristics:

- Standard fish prompt characters: > for user, # for root
- Uses the fish `prompt_pwd`, so paths will be abbreviated
- Uses built-in `__fish_git_prompt` functionality
- Indicates Git work-in-progress (gwip/gunwip) if detected
- Prompt character is colored red if previous command had a non-zero exit
  status
- Includes complementary `LS_COLORS`

### Configuration:

- Disable Solarized colors in prompt with: `set -U yimmy_solarized false`

### cmd's modifications

* git info after hostname info
* support for `virtualfish` added
