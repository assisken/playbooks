# playbooks

## The purpose and specifics

I use this repository just to save, pull and apply a configurations for several machines.

Limitations:

- Archlinux-specific: AUR is allowed;
- There may be Raspberry PI specific configs.

## Why I use Ansible

I want to save, reuse and synchronize my configuration and some system-wide setup for long therm usage.

What I have tried to use before:

1. Puppet.
    
    It's overkill for a daily home usage. You do need to setup certs and other very secure stuff. Usable for large systems, not for some small home environment.

2. NixOS.

    Pros: the idea.
    
    Cons:
    - non-general-purpose, very specific programming language (why not just use a simple DSL powered by any of popular programming languages such as Ruby, Rust or something?);
    - such pain for patching some software for Linux but not for the Unix world, writing extensions for mutable software.
