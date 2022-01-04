# Getting Started

Noritex Styled Components SDK allows users to style your website using the necesary CSS only withouth having to import a big library.

Regardless of the technologies and tools behind them, a successful design system follows these guiding principles:

-   **It’s consistent**. The way components are built and managed follows a predictable pattern.

-   **It’s self-contained**. Your design system is treated as a standalone dependency.

-   **It’s reusable**. You’ve built components so they can be reused in many contexts.

-   **It’s accessible**. Applications built with your design system are usable by as many people as possible.

-   **It’s robust**. No matter the product or platform to which your design system is applied, it should perform with grace and minimal bugs.

## Install

    npm install noritex-sdk

## 3 Files

Elements.js

Form.js

Layout.js

    import {
        Pagination,
        Filters,
        Tag,
        Tabs,
        Modal,
        Preloader,
        Dropdown,
        Breadcrumb,
        ArrowLeft,
        ArrowRight,
        Menu,
        Profile,
        Notify,
        Message
    } from "noritex-sdk/Elements";

    import {
        Control,
        Field,
        FieldBody,
        SelectBox,
        Checkbox,
        Radio
    } from "noritex-sdk/Form";

    import {
        Section,
        Box,
        Container,
        Row,
        Column,
        Columns,
        Content,
        Title,
        Subtitle,
        Heading,
        BlankState,
        LevelLeft,
        LevelRight,
        LevelItem,
        Level,
        SimpleCard,
        PageContent
    } from "noritex-sdk/Layout";

## Extend the components

    import {
    	    Checkbox,
    } from "noritex-sdk/Form";

    const CheckboxExtended = styled(Checkbox)`
    	padding: 10px
    `;

## Components

Slider.js
// todo
