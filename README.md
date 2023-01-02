# ansible-agate

## An easy way to deploy the Agate Gemini server!
Agate is a simple Gemini server written in the Rust language. 
https://github.com/mbrubeck/agate

## Supported architectures
- x86-64
- ARMv7
- aarch

## Supported Operating systems
- Ubuntu
- Armbian

This ansible role downloads the agate binary corresponding to the architecture of your ansible target. You cna checkout a git repository with the parameter `gemini_content_url` and its content will be placed into `/srv/gemini/capsule`.