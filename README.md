

Deleted (or changed into location.replace()):
function performFastExit(event) {
        event.preventDefault(); // Prevent default link behavior if it's an anchor
        // Redirect to a neutral, common website
        window.location.href = 'https://www.google.com';
    }
