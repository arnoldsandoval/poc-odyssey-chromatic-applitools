---
template: component
id: component-section-message
title: Section Message
description:
lead:
tabs:
  - label: 'Overview'
    id: 'overview'
  - label: 'HTML & SCSS'
    id: 'html-scss'
links:
  - icon: github
    label: View source
    href: https://github.com/okta/odyssey/blob/master/packages/odyssey/src/scss/components/_section-message.scss
  - icon: figma
    label: View designs
    href:
---

::: slot overview

## Anatomy

## Behavior

## Variants

### Success

<Description>

Used for reporting successful actions, results, or states to the user. This variant utilizes an alternate link style to satisfy contrast requirements for on-color backgrounds.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-success is-ods-section-message-blv">
      <span class="ods-section-message--icon">
        <OdsIcon icon="complete"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Ready for lift-off</h1>
      <section class="ods-section-message--content">
        <p>Safety checks are complete, and this mission as been approved for launch.</p>
      </section>
      <section class="ods-section-message--actions">
        <a href="#">View countdown</a>
      </section>
    </aside>
  </template>
</Visual>

<Description>

Used for reporting successful actions, results, or states to the user. This alternate style maintains a white background.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-success is-ods-section-message-alt">
      <span class="ods-section-message--icon">
        <OdsIcon icon="complete"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Ready for lift-off</h1>
      <section class="ods-section-message--content">
        <p>Safety checks are complete, and this mission as been approved for launch.</p>
      </section>
      <section class="ods-section-message--actions">
        <a href="#">View countdown</a>
      </section>
    </aside>
  </template>
</Visual>

<Description>

Used for reporting successful actions, results, or states to the user. This showcases inline linking.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-success is-ods-section-message-alt">
      <span class="ods-section-message--icon">
        <OdsIcon icon="complete"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Ready for lift-off</h1>
      <section class="ods-section-message--content">
        <p>Safety checks are complete, and this mission as been approved for launch. You may <a href="#">view the countdown</a> prior to lift-off.</p>
      </section>
    </aside>
  </template>
</Visual>

### Caution

<Description>

Used to inform users of tasks or processes that may need their attention.

When using the Caution variant, ensure the user does not need more context than you can give in the space available.

This variant utilizes an alternate link style to satisfy contrast requirements for on-color backgrounds.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-caution is-ods-section-message-blv">
      <span class="ods-section-message--icon">
        <OdsIcon icon="caution"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Safety checks incomplete</h1>
      <section class="ods-section-message--content">
        <p>Safety checks must be completed before this mission as been approved for launch.</p>
      </section>
      <section class="ods-section-message--actions">
        <a href="#">Begin safety checks</a>
      </section>
    </aside>
  </template>
</Visual>

<Description>

Used to inform users of tasks or processes that may need their attention.

When using the Caution variant, ensure the user does not need more context than you can give in the space available.

This alternate style maintains a white background.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-caution is-ods-section-message-alt">
      <span class="ods-section-message--icon">
        <OdsIcon icon="caution"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Safety checks incomplete</h1>
      <section class="ods-section-message--content">
        <p>Safety checks must be completed before this mission as been approved for launch.</p>
      </section>
      <section class="ods-section-message--actions">
        <a href="#">Begin safety checks</a>
      </section>
    </aside>
  </template>
</Visual>

<Description>

Used to inform users of tasks or processes that may need their attention.

When using the Caution variant, ensure the user does not need more context than you can give in the space available.

This showcases inline linking.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-caution is-ods-section-message-alt">
      <span class="ods-section-message--icon">
        <OdsIcon icon="caution"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Safety checks incomplete</h1>
      <section class="ods-section-message--content">
        <p>You'll need to <a href="#">complete safety checks</a> before this mission as been approved for launch.</p>
      </section>
    </aside>
  </template>
</Visual>

### Danger

<Description>

Use Danger messages to inform users that an error has occurred. This variant utilizes an alternate link style to satisfy contrast requirements for on-color backgrounds.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-danger is-ods-section-message-blv">
      <span class="ods-section-message--icon">
        <OdsIcon icon="error"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Safety checks have failed</h1>
      <section class="ods-section-message--content">
        <p>An issue has been discovered with your fuel mixture ratios. Please correct this and perform safety checks again.</p>
      </section>
      <section class="ods-section-message--actions">
        <a href="#">Configure fuel mixture</a>
      </section>
    </aside>
  </template>
</Visual>

<Description>

Use Danger messages to inform users that an error has occurred. This alternate style maintains a white background.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-danger is-ods-section-message-alt">
      <span class="ods-section-message--icon">
        <OdsIcon icon="error"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Safety checks have failed</h1>
      <section class="ods-section-message--content">
        <p>An issue has been discovered with your fuel mixture ratios. Please <a href="#">reconfigure your fuel mixture</a> and perform safety checks again.</p>
      </section>
    </aside>
  </template>
</Visual>

<Description>

Use Danger messages to inform users that an error has occurred. This showcases inline linking.

</Description>

<Visual content="full">
  <template>
    <aside class="ods-section-message is-ods-section-message-danger is-ods-section-message-alt">
      <span class="ods-section-message--icon">
        <OdsIcon icon="error"></OdsIcon>
      </span>
      <h1 class="ods-section-message--title">Safety checks have failed</h1>
      <section class="ods-section-message--content">
        <p>An issue has been discovered with your fuel mixture ratios. Please correct this and perform safety checks again.</p>
      </section>
      <section class="ods-section-message--actions">
        <a href="#">Configure fuel mixture</a>
      </section>
    </aside>
  </template>
</Visual>

## Usage

## Content Guidelines

## Accessibility

## References

### Related components

<Description>

- <a href="/components/toast">Toast</a>

</Description>

### Further reading

:::

::: slot html-scss

## Primary

<figure class="docs-example">
  <div class="docs-example--rendered">
    <button class="ods-button">
      <span class="ods-button--label">Primary</span>
    </button>
    <button class="ods-button is-ods-button-hover">
      <span class="ods-button--label">Hover</span>
    </button>
    <button class="ods-button is-ods-button-focus">
      <span class="ods-button--label">Focus</span>
    </button>
    <button class="ods-button" disabled>
      <span class="ods-button--label">Disabled</span>
    </button>
  </div>

  ```html
  <button class="ods-button">
    <span class="ods-button--label">Primary</span>
  </button>
  <button class="ods-button" disabled>
    <span class="ods-button--label">Primary</span>
  </button>
  ```
</figure>

## Accessibility

<Description>

In addition to the above use-cases for Icon, consider using the `<button>` element instead of `<a>` whenever possible. The keyboard and screen reader interaction for these elements is different. Space will trigger a `<button>`; Enter will trigger an `<a>`.

</Description>
:::