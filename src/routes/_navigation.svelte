<script lang="ts">
    import {
        Nav,
        NavbarBrand,
        NavLink,
        Navbar,
        NavItem
    } from 'sveltestrap';
</script>

<Navbar expand="md">
    <NavbarBrand href="/">Nyalpeh</NavbarBrand>
    <Nav class="me-auto" navbar>
        <NavItem>
            <NavLink href="/about">About</NavLink>
        </NavItem>
        <NavItem>
            <NavLink href="/contact">Contact</NavLink>
        </NavItem>
    </Nav>
</Navbar>