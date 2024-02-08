# JavaScript-Q12
Write a JavaScript program that uses a try-catch block to catch and handle a 'ReferenceError' when accessing an undefined variable.

function access_Variable() {
  try {
    console.log(undefinedVariable);
  } catch (error) {
    if (error instanceof ReferenceError) {
      console.log('ReferenceError:', error.message);
    } else {
      console.log('Error:', error.message);
    }
  }
}

// Example:
access_Variable();
