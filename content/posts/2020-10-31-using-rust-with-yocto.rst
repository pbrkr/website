Demo: Using Rust with Yocto Project
===================================

:date: 2020-10-31
:tags: yocto, rust, linux, embedded-linux, conference-talks, license-compliance
:summary: I gave a presentation and demo on "Using Rust with Yocto Project"
    at the Yocto Project (Virtual) Summit Europe 2020 on 22nd October 2020. I
    introduced a couple of simple applications written in Rust and showed how
    to use the ``cargo-bitbake`` tool to automatically generate Yocto Project
    recipes for each project. I also discussed how the Cargo build tool and
    package manager interacts with the license compliance features provided
    by Yocto Project.

Summary
-------

The Rust programming language has been named the "most loved programming
language" in the Stack Overflow Developer Survey every year since 2016.
However, many Embedded Linux developers are unfamiliar with this language and
with the benefits it can provide. There is also a knowledge gap on how to
build and deploy software written in Rust using OpenEmbedded and Yocto
Project.

This session will focus on demonstrating how to use Rust with Yocto Project.
Two basic applications will be written along with the metadata needed by the
Cargo build tool. Yocto Project recipes will be generated for each
application and added to a layer. An image will then be built containing both
applications and this will be tested out under qemu. In addition some brief
thoughts on how Rust and the Cargo build tool interact with the license
compliance features of Yocto Project will be discussed. This talk is aimed at
an intermediate audience. No familiarity with the Rust programming language
is assumed.

Video
-----

.. youtube:: p1X2fBER57A

Slides
------

.. raw:: html

    <div style="position:relative; padding-bottom:65%; margin-bottom: 1.4em">
        <iframe style="width:100%; height:100%; position:absolute; left:0px; top:0px;"
            src="//www.slideshare.net/slideshow/embed_code/key/3NektSNMNBAgUu"
            frameborder="0" marginwidth="0" marginheight="0" scrolling="no" allowfullscreen>
        </iframe>
    </div>
