<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<form name="netlify-form-test" method="POST" netlify-honeypot="nbot-field" data-netlify="true">
    <input type="hidden" name="form-name" value="netlify-form-test"/>
    <label for="name">Name</label>
    <input name="name" id="name" required placeholder="Name" type="text"/> 
    <label for="email">Email</label>
    <input name="email" id="email" required placeholder="Email" type="text"/> 
    <input type="submit" value="Submit"/>
</form>