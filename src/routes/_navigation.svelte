<script lang="ts">
    import {
        Nav,
        NavbarBrand,
        NavLink,
        Navbar,
        NavItem
    } from 'sveltestrap';

    const links = [
        {path: "/contact", display: "Contact"},
    ]
</script>

<Navbar expand="md">
    <NavbarBrand href="/">Nyaleph</NavbarBrand>
    <Nav class="me-auto" navbar>
        {#each links as link}
        <NavItem>
            <NavLink href={link.path}>{link.display}</NavLink>
        </NavItem>
        {/each}
    </Nav>
</Navbar>