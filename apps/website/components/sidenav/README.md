---
title: Overview
toc: true
---

<div cds-layout="pl@md:sm" class="alert alert-warning">
    <div class="alert-items">
        <div class="alert-item static" role="alert">
            <div class="alert-icon-wrapper">
                <clr-icon class="alert-icon" shape="exclamation-circle"></clr-icon>
            </div>
            <span class="alert-text">
                Sidenav has been deprecated but does not have a targeted version for removal. The recommendation for this pattern is to use the <a href="/components/vertical-nav/">vertical nav</a> component.
            </span>
        </div>
    </div>
</div>

# Sidenav

The sidenav is a left-aligned navigational component.

## Usage

When there are many navigation links a side navigation provides overflow and scrolling to the list of links. Users are informed when a navigation item is active.

Use the sidenav:

- For links secondary to the links in the header or subnav
- For a navigation schema with a deep hierarchy
- When the header and subnav cannot accommodate the required links

The sidenav works best in desktop applications. Scroll when the content exceeds the viewport.

## Anatomy

### Structure

Clarity [application layout](/foundation/app-layout/) depends on a specific DOM structure for layout to work properly. SIde nav fits into this and has a specific place in the DOM hierarchy. A Sidenav container is a sibling element of the content area.

<doc-demo src="/demos/sidenav/structure-ng.html" demo="/demos/sidenav/structure-css.html" />

### Navigation Groups

Naviagation groups provide a way to group similar or related links together. When grouping links, do not make the heading a link.

<doc-demo src="/demos/sidenav/nav-groups-ng.html" demo="/demos/sidenav/nav-groups-css.html" />

### Icons

Using Icons
Include icons when you want to provide a more appealing visual look than just text.

<doc-demo src="/demos/sidenav/icons-ng.html" demo="/demos/sidenav/icons-css.html" />