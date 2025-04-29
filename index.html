<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haawa</title>

    <script src="https://unpkg.com/react@18/umd/react.development.js" crossorigin></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js" crossorigin></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&display=swap" rel="stylesheet">

    <style>
        /* --- Very Dark Theme (Variables slightly adjusted if needed) --- */
        :root {
            /* Base Dark Colors */
            --bg-dark-primary: #0d1117;
            --bg-dark-secondary: #161b22;
            --bg-container: #1c2128;
            --border-color: rgba(139, 148, 158, 0.2);
            --text-primary: #e6edf3;
            --text-secondary: #7d8590;

            /* Accent Colors */
            --accent-deep-blue: #1f6feb;
            --accent-deep-blue-darker: #1458b8;
            --accent-muted-teal: #3fb950;
            --accent-muted-teal-darker: #2da44e;

            /* Social Colors */
            --accent-facebook: #388bfd; /* Adjusted slightly */
            --accent-instagram: #e4405f;

            /* Status Colors */
            --success-color: var(--accent-muted-teal);
            --success-color-light: rgba(63, 185, 80, 0.15);
            --error-color: #f85149;

            /* Input Styles */
            --input-bg: #0d1117;
            --input-border: #30363d;
            --input-border-focus: var(--accent-deep-blue);
            --input-placeholder-color: #484f58;

            /* Shadows */
            --shadow-medium: 0 6px 18px rgba(0, 0, 0, 0.4);
            --shadow-large: 0 12px 36px rgba(0, 0, 0, 0.5);

             /* Transitions */
            --transition-fast: all 0.2s ease-in-out;
            --transition-bounce: transform 0.1s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        *, *::before, *::after {
            box-sizing: border-box; margin: 0; padding: 0;
        }
        body {
            font-family: 'Cairo', sans-serif;
            background-color: var(--bg-dark-primary);
            color: var(--text-primary);
            line-height: 1.6; min-height: 100vh;
            overflow-x: hidden; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale;
        }
        #root { min-height: 100vh; display: flex; flex-direction: column; }
        .visually-hidden { position: absolute; width: 1px; height: 1px; margin: -1px; padding: 0; overflow: hidden; clip: rect(0, 0, 0, 0); border: 0; }

        /* --- Header --- */
        .app-header {
            background-color: rgba(13, 17, 23, 0.85);
            padding: 15px 40px; display: flex;
            justify-content: space-between; align-items: center; backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border-color);
            position: sticky; top: 0; z-index: 1000;
        }

        /* --- Logo --- */
        .haawa-logo {
            font-size: 2em; font-weight: 900;
            color: var(--accent-deep-blue);
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
            cursor: pointer; letter-spacing: 1px;
        }

        /* --- Navigation --- */
        .nav-links button {
            background: none; border: none;
            color: var(--text-secondary);
            font-family: inherit;
            font-size: 0.95em; margin-left: 25px; cursor: pointer; padding: 8px 12px;
            border-radius: 6px; transition: var(--transition-fast), transform 0.1s ease; /* Added transform transition */
            display: inline-flex; align-items: center; gap: 6px;
            position: relative;
        }
        .nav-links button:hover {
            background-color: rgba(255, 255, 255, 0.05);
            color: var(--text-primary);
        }
        .nav-links button i {
             transition: var(--transition-bounce);
        }
        /* --- Icon Click Effect --- */
        .nav-links button:active {
            background-color: rgba(255, 255, 255, 0.1); /* Slightly darker feedback */
            transform: scale(0.95); /* Button click effect */
        }
        .nav-links button:active i {
            transform: scale(0.9);
        }

        /* --- Main Content Area --- */
        .view-container { flex-grow: 1; padding: 60px 40px; display: flex; justify-content: center; align-items: flex-start; animation: fadeInView 0.5s ease-out forwards; }
        @keyframes fadeInView { from { opacity: 0; } to { opacity: 1; } }
        .main-content { width: 100%; max-width: 1100px; }

        /* --- Welcome Header --- */
        .welcome-header { margin-bottom: 40px; padding-bottom: 20px; border-bottom: 1px solid var(--border-color); }
        .welcome-header h1 { font-size: 2.2em; font-weight: 700; margin-bottom: 5px; color: var(--text-primary); }
        .welcome-header p { font-size: 1.1em; color: var(--text-secondary); }

        /* --- Login Form --- */
        .login-wrapper { width: 100%; display: flex; flex-direction: column; justify-content: center; align-items: center; flex-grow: 1; padding: 20px; }
        .login-container {
            background-color: var(--bg-container);
            padding: 50px 60px; border-radius: 12px;
            box-shadow: var(--shadow-large);
            max-width: 480px; width: 100%; text-align: center;
            border: 1px solid var(--border-color);
            animation: scaleUp 0.5s cubic-bezier(0.165, 0.84, 0.44, 1) forwards;
        }
        @keyframes scaleUp { from { opacity: 0; transform: scale(0.9); } to { opacity: 1; transform: scale(1); } }
        .login-logo {
            font-size: 2.5em; font-weight: 900; margin-bottom: 35px; letter-spacing: 1px;
            color: var(--accent-deep-blue);
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }
        .login-title { font-size: 1.6em; font-weight: 700; margin-bottom: 30px; color: var(--text-primary); }
        .form-group { margin-bottom: 25px; text-align: right; }
        .form-group label { display: block; margin-bottom: 8px; font-weight: 700; color: var(--text-secondary); font-size: 0.95em; }
        .form-group input {
            width: 100%; padding: 15px 20px;
            border: 1px solid var(--input-border);
            border-radius: 8px;
            background-color: var(--input-bg);
            color: var(--text-primary);
            font-size: 1em; font-family: inherit; transition: var(--transition-fast);
        }
        .form-group input:focus {
            outline: none;
            border-color: var(--input-border-focus);
            box-shadow: 0 0 0 3px rgba(31, 111, 235, 0.3);
        }
        .form-group input::placeholder { color: var(--input-placeholder-color); }

        /* --- Dark Button (Primary Action) --- */
        .form-button {
            padding: 15px 40px; width: 100%;
            background: linear-gradient(145deg, var(--accent-deep-blue-darker), var(--accent-deep-blue));
            color: #ffffff;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
            border: none; font-weight: 700; border-radius: 8px;
            font-size: 1.1em; cursor: pointer;
            transition: var(--transition-fast), transform 0.15s ease;
            margin-top: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            display: inline-flex; justify-content: center; align-items: center; gap: 8px;
             position: relative;
        }
        .form-button:hover {
             background: linear-gradient(145deg, var(--accent-deep-blue), var(--accent-deep-blue-darker));
             transform: translateY(-2px);
             box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
        }
        /* --- Button Click Effect --- */
        .form-button:active {
            transform: translateY(0px) scale(0.98); /* Combine effects */
            background: var(--accent-deep-blue-darker);
             box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }
        .form-button:disabled {
            background: var(--text-secondary);
            cursor: not-allowed; opacity: 0.6; transform: none; box-shadow: none;
            text-shadow: none;
        }
        /* --- Icon Click Effect (within button) --- */
        .form-button i {
             display: inline-block;
             transition: var(--transition-bounce);
         }
        .form-button:active i {
             transform: scale(0.85);
         }

        .error-message { color: var(--error-color); font-weight: 700; margin-top: -10px; margin-bottom: 15px; min-height: 1.2em; font-size: 0.9em; }

        /* --- Home Dashboard (Social Cards Area) --- */
        .dashboard-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 35px; }
        .social-card-pro {
            background-color: var(--bg-container);
            border-radius: 12px; padding: 30px;
            border: 1px solid var(--border-color);
            box-shadow: var(--shadow-medium);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            display: flex; flex-direction: column; opacity: 0; transform: translateY(20px); animation: slideUpFadeIn 0.5s ease-out forwards;
        }
        @keyframes slideUpFadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .social-card-pro:hover {
            transform: translateY(-8px);
            box-shadow: var(--shadow-large);
        }
        .card-header { display: flex; align-items: center; margin-bottom: 25px; padding-bottom: 15px; border-bottom: 1px solid var(--border-color); }
        .card-icon { font-size: 2.8em; margin-left: 15px; flex-shrink: 0; line-height: 1; }
        .card-icon.facebook { color: var(--accent-facebook); }
        .card-icon.instagram { color: var(--accent-instagram); }
        .card-title { font-size: 1.4em; font-weight: 700; flex-grow: 1; color: var(--text-primary); }
        .status-indicator { width: 10px; height: 10px; border-radius: 50%; background-color: var(--success-color); margin-right: 10px; box-shadow: 0 0 8px var(--success-color); }
        .card-body { flex-grow: 1; margin-bottom: 30px; }
        .card-body p { color: var(--text-secondary); font-size: 0.95em; margin-bottom: 15px; }
        .info-placeholder {
             background-color: rgba(13, 17, 23, 0.7);
             border-radius: 6px; height: 40px; margin-bottom: 10px;
             animation: pulsePlaceholderDark 1.5s infinite ease-in-out;
         }
        @keyframes pulsePlaceholderDark { 0% { opacity: 0.6; } 50% { opacity: 1; } 100% { opacity: 0.6; } }
        .card-actions { margin-top: auto; }
        /* Action button inherits .form-button styles */
        .card-actions .action-button { width: 100%; padding: 12px 20px; font-size: 1em; }
         /* Ensure :active styles apply to card buttons too */
        .card-actions .action-button:active {
            transform: translateY(0px) scale(0.98);
            background: var(--accent-deep-blue-darker);
        }
        .card-actions .action-button:active i {
            transform: scale(0.85);
        }


        /* --- Modal Styles --- */
        .modal-overlay { position: fixed; inset: 0; background-color: rgba(0, 0, 0, 0.75); backdrop-filter: blur(5px); display: flex; justify-content: center; align-items: center; z-index: 1100; opacity: 0; animation: fadeInModal 0.3s ease forwards; }
        .modal-content {
            background-color: var(--bg-container);
            padding: 40px; border-radius: 10px;
            box-shadow: var(--shadow-large);
            max-width: 500px; width: 90%;
            border: 1px solid var(--border-color);
            position: relative; opacity: 0; transform: scale(0.9); animation: scaleUpModal 0.4s 0.1s cubic-bezier(0.165, 0.84, 0.44, 1) forwards;
        }
        @keyframes fadeInModal { to { opacity: 1; } }
        @keyframes scaleUpModal { to { opacity: 1; transform: scale(1); } }
        .modal-close-button {
            position: absolute; top: 15px; left: 15px; background: none; border: none;
            color: var(--text-secondary); font-size: 1.8em; cursor: pointer;
            line-height: 1; padding: 5px; transition: var(--transition-fast), transform 0.1s ease; /* Added transform */
        }
        .modal-close-button:hover { color: var(--text-primary); }
        /* --- Close Button Click Effect --- */
        .modal-close-button:active {
            transform: scale(0.85);
            color: var(--error-color); /* More prominent click feedback */
         }
        .modal-content h2 {
             font-size: 1.6em; margin-bottom: 25px; text-align: center;
             color: var(--accent-deep-blue);
        }
        .modal-error-message {
            color: var(--error-color); font-weight: normal;
            margin-top: 10px; text-align: right; font-size: 0.9em;
            min-height: 1.2em;
        }

        /* -- Modal Account Creation Success -- */
        .account-creation-success {
            padding: 25px; margin-top: 20px; border-radius: 8px;
            background-color: var(--success-color-light);
            border: 1px solid rgba(63, 185, 80, 0.2);
            text-align: center;
        }
        .account-creation-success h3 {
            color: var(--success-color); font-size: 1.3em; margin-bottom: 15px;
            display: flex; align-items: center; justify-content: center; gap: 10px;
        }
        .account-creation-success p { color: var(--text-secondary); margin-bottom: 20px; font-size: 1em; line-height: 1.7; }
        .credential-display {
            background-color: rgba(13, 17, 23, 0.6);
            padding: 15px 20px; border-radius: 6px; margin-bottom: 15px;
            display: flex; justify-content: space-between; align-items: center;
            border: 1px solid var(--border-color);
        }
        .credential-text {
            font-family: monospace; font-size: 1.1em;
            color: var(--text-primary);
            direction: ltr; text-align: left; word-break: break-all;
            margin-left: 15px; flex-grow: 1;
        }
        /* --- Dark Copy Button --- */
        .copy-button {
            background-color: var(--input-bg);
            border: 1px solid var(--input-border);
            color: var(--text-secondary);
            padding: 8px 12px; border-radius: 6px; cursor: pointer;
            transition: var(--transition-fast), transform 0.1s ease; /* Added transform */
            font-size: 0.85em; display: inline-flex; align-items: center; gap: 6px; flex-shrink: 0;
             position: relative;
        }
        .copy-button:hover {
            background-color: var(--input-border);
            color: var(--text-primary);
        }
        .copy-button.copied {
             background-color: var(--success-color);
             color: #ffffff;
             border-color: var(--success-color);
         }
        /* --- Copy Button Click Effect --- */
        .copy-button:active {
            transform: scale(0.95); /* Click effect */
            background-color: var(--input-border); /* Consistent active bg */
         }
        .copy-button.copied:active {
            background-color: var(--accent-muted-teal-darker); /* Darker green on click when copied */
        }
        .copy-button i {
            display: inline-block;
             transition: var(--transition-bounce);
         }
        .copy-button:active i {
             transform: scale(0.85);
         }

         /* --- Dark Close Button in Modal Success --- */
        .modal-close-action { margin-top: 30px; text-align: center; }
        .modal-close-action .form-button { /* Reusing .form-button but styling as secondary */
            width: auto; padding: 12px 35px;
            background: var(--bg-dark-secondary); /* Use secondary bg */
            color: var(--text-primary);
            box-shadow: none;
            border: 1px solid var(--input-border);
            font-weight: 400;
            text-shadow: none;
            /* Ensure transitions apply */
            transition: var(--transition-fast), transform 0.1s ease;
         }
         .modal-close-action .form-button:hover {
             background: var(--input-border);
             transform: none; /* Override hover transform from primary .form-button */
             box-shadow: none;
         }
         /* --- Modal Close Action Click Effect --- */
        .modal-close-action .form-button:active {
            background: var(--border-color); /* Slightly darker on click */
            transform: scale(0.98); /* Subtle click scale */
        }
        .modal-close-action .form-button:active i {
            transform: scale(0.85);
        }


        /* --- Responsive Adjustments --- */
        @media (max-width: 768px) {
             .app-header { padding: 15px 20px; }
             .view-container { padding: 40px 20px; }
             .login-container { padding: 40px 30px; }
             .dashboard-grid { grid-template-columns: 1fr; }
             .credential-display { flex-direction: column; align-items: flex-start; gap: 10px; }
             .credential-text { margin-left: 0; font-size: 1em; width: 100%; }
             .copy-button { align-self: flex-end; }
        }
        @media (max-width: 480px) {
             .haawa-logo { font-size: 1.6em; }
             .nav-links button { margin-left: 10px; font-size: 0.9em; }
             .login-logo { font-size: 2em; }
             .login-title { font-size: 1.3em; }
             .form-group input, .form-button { font-size: 0.95em; padding: 12px 15px; }
             .welcome-header h1 { font-size: 1.8em; }
             .social-card-pro { padding: 25px; }
             .card-title { font-size: 1.2em; }
             .card-icon { font-size: 2.4em; }
             .modal-content { padding: 30px 20px; }
             .modal-content h2 { font-size: 1.4em; }
             .account-creation-success h3 { font-size: 1.2em; }
             .account-creation-success p { font-size: 0.95em; }
             .credential-text { font-size: 0.9em; }
             .copy-button { font-size: 0.8em; padding: 6px 10px; }
             .modal-close-action .form-button { padding: 10px 25px; } /* Adjust padding */
        }

    </style>
</head>
<body>
    <div id="root"></div>

    <script type="text/babel">
        const { useState, useEffect, useCallback, useRef } = React;

        // --- Helper: Copy to Clipboard ---
        function copyToClipboard(text) {
            if (navigator.clipboard && window.isSecureContext) {
                return navigator.clipboard.writeText(text);
            } else {
                // Fallback for insecure contexts or older browsers
                const textArea = document.createElement("textarea");
                textArea.value = text;
                textArea.style.position = "fixed"; // Use fixed to avoid scrolling issues
                textArea.style.top = "-9999px";
                textArea.style.left = "-9999px";
                textArea.style.opacity = "0";
                textArea.style.pointerEvents = "none";
                document.body.appendChild(textArea);
                textArea.focus();
                textArea.select();
                try {
                    const successful = document.execCommand('copy');
                    document.body.removeChild(textArea);
                    return successful ? Promise.resolve() : Promise.reject(new Error('Copy command failed'));
                } catch (err) {
                    document.body.removeChild(textArea);
                    return Promise.reject(err);
                }
            }
        }

        // --- Logo Component ---
        function HaawaLogo({ onClick }) {
            return <div className="haawa-logo" onClick={onClick}>Haawa</div>;
        }

        // --- Header Component ---
        function Header({ navigateTo, logout, isLoggedIn }) {
            return (
                <header className="app-header">
                    <HaawaLogo onClick={() => isLoggedIn ? navigateTo('home') : null} />
                    {isLoggedIn && (
                        <nav className="nav-links">
                            <button onClick={logout}>
                                <i className="fas fa-sign-out-alt"></i> تسجيل الخروج
                            </button>
                        </nav>
                    )}
                </header>
            );
        }

        // --- Professional Social Card ---
        function SocialCardPro({ platform, iconClass, onSetupAccount, delay }) {
            const platformName = platform === 'facebook' ? 'فيسبوك' : 'انستغرام';
            const iconColorClass = platform;
            const style = { animationDelay: `${delay}s` };
            // Adjust button text based on whether it creates dummy data
            const createsDummyData = platform === 'instagram' || platform === 'facebook';
            const buttonText = createsDummyData ? 'إنشاء / إدارة حساب وهمي' : 'إعداد / إدارة الحساب';
            const buttonIcon = createsDummyData ? 'fa-user-plus' : 'fa-cog';

            return (
                <div className="social-card-pro" style={style}>
                    <div className="card-header">
                        <i className={`fab ${iconClass} card-icon ${iconColorClass}`}></i>
                        <h3 className="card-title">{platformName}</h3>
                        <div className="status-indicator" title="الحالة: متصل (وهمي)"></div>
                    </div>
                    <div className="card-body">
                        <p>إدارة و{createsDummyData ? 'إنشاء حساب وهمي' : 'إعداد حساب'} {platformName} الخاص بك.</p>
                         <div className="info-placeholder"></div>
                         <div className="info-placeholder" style={{width: '70%'}}></div>
                    </div>
                    <div className="card-actions">
                        <button className="form-button action-button" onClick={() => onSetupAccount(platform)}>
                             <i className={`fas ${buttonIcon}`} style={{marginLeft: '8px'}}></i> {buttonText}
                        </button>
                    </div>
                </div>
            );
        }

         // --- Registration/Setup Modal ---
         function SetupAccountModal({ platform, closeModal, onAccountSetup }) {
            const [username, setUsername] = useState('');
            const [apiKey, setApiKey] = useState(''); // State for Optional API Key
            const [error, setError] = useState('');
            const [isAccountCreated, setIsAccountCreated] = useState(false);
            const [dummyEmail, setDummyEmail] = useState('');
            const [dummyPassword, setDummyPassword] = useState('');
            const [emailCopied, setEmailCopied] = useState(false);
            const [passwordCopied, setPasswordCopied] = useState(false);

            const platformName = platform === 'facebook' ? 'فيسبوك' : 'انستغرام';
            const canCreateDummy = platform === 'facebook' || platform === 'instagram';
            const usernameInputRef = useRef(null);

            useEffect(() => {
                if (!isAccountCreated && usernameInputRef.current) {
                    usernameInputRef.current.focus();
                }
            }, [isAccountCreated]);

            const handleCreateAccount = (event) => {
                event.preventDefault();
                setError('');
                setEmailCopied(false);
                setPasswordCopied(false);

                if (!username.trim()) {
                    setError('الرجاء إدخال اسم المستخدم.');
                    return;
                }

                 // Optional: Add API Key validation here if needed
                 // console.log("API Key Entered:", apiKey);

                if (canCreateDummy) { // Check if platform supports dummy creation
                    try {
                        const cleanedUsername = username.trim().replace(/\s+/g, '_').toLowerCase();
                        const randomString = Math.random().toString(36).substring(2, 8);
                        // --- Generate domain based on platform ---
                        const domain = platform === 'instagram' ? 'haawa.insta' : 'haawa.fb';
                        const generatedEmail = `${cleanedUsername}_${randomString}@${domain}`;
                        const generatedPassword = `HaaWaP_${Math.random().toString(36).substring(2, 10)}`;

                        setDummyEmail(generatedEmail);
                        setDummyPassword(generatedPassword);
                        setIsAccountCreated(true);
                        // Pass username, dummy credentials (and optional API key) to callback
                        onAccountSetup(platform, username, generatedEmail, generatedPassword, apiKey);

                    } catch (e) {
                        console.error("Error during credential generation:", e);
                        setError("حدث خطأ أثناء إنشاء البيانات الوهمية.");
                        setIsAccountCreated(false);
                    }
                } else {
                    // Handle setup for other platforms (if any)
                    onAccountSetup(platform, username, null, null, apiKey); // Pass username and API key
                    closeModal(); // Close immediately if not creating dummy data
                }
            };

            const handleCopy = (textToCopy, type) => {
                 copyToClipboard(textToCopy)
                    .then(() => {
                        if (type === 'email') {
                            setEmailCopied(true);
                            setTimeout(() => setEmailCopied(false), 2000);
                         } else if (type === 'password') {
                             setPasswordCopied(true);
                             setTimeout(() => setPasswordCopied(false), 2000);
                         }
                         setError(''); // Clear previous errors on successful copy
                    })
                    .catch(err => {
                        console.error(`Failed to copy ${type}: `, err);
                        // Update error state to show copy failure message
                        setError(`فشل نسخ ${type === 'email' ? 'البريد' : 'كلمة المرور'}. حاول مرة أخرى يدويًا.`);
                     });
             };

             const handleKeyDown = useCallback((event) => {
                 if (event.key === 'Escape') {
                     closeModal();
                 }
             }, [closeModal]);

             useEffect(() => {
                 document.addEventListener('keydown', handleKeyDown);
                 return () => {
                     document.removeEventListener('keydown', handleKeyDown);
                 };
             }, [handleKeyDown]);

             // --- Adjust Modal Title ---
             const actionVerb = canCreateDummy ? 'إنشاء' : 'إعداد';
             const modalTitle = isAccountCreated
                ? `تم إنشاء حساب ${platformName} وهمي`
                : `${actionVerb} حساب ${platformName}`;

            return (
                <div className="modal-overlay" onClick={closeModal}>
                     <div className="modal-content" onClick={(e) => e.stopPropagation()}>
                         <button className="modal-close-button" onClick={closeModal} aria-label="إغلاق">
                             <i className="fas fa-times"></i>
                         </button>
                         <h2>{modalTitle}</h2>

                         {!isAccountCreated ? (
                             <form onSubmit={handleCreateAccount}>
                                 <div className="form-group">
                                     <label htmlFor="modal-username">
                                        {`اسم المستخدم المطلوب لـ ${platformName}`}
                                     </label>
                                     <input
                                        ref={usernameInputRef} type="text" id="modal-username"
                                        value={username} onChange={(e) => { setUsername(e.target.value); setError(''); }}
                                        placeholder="أدخل اسم المستخدم هنا" required aria-describedby="modal-error"
                                     />
                                 </div>

                                 {/* --- Optional API Key Input Field --- */}
                                 {/* Remove comments below to enable the API Key field */}
                                 {/*
                                 <div className="form-group" style={{marginTop: '20px'}}>
                                     <label htmlFor="modal-api-key" style={{ display: 'flex', alignItems: 'center', gap: '8px' }}>
                                         <i className="fas fa-key" style={{ color: 'var(--text-secondary)' }}></i>
                                         مفتاح API (اختياري)
                                     </label>
                                     <input
                                        type="password" // Use password to mask the key
                                        id="modal-api-key"
                                        value={apiKey}
                                        onChange={(e) => setApiKey(e.target.value)}
                                        placeholder="أدخل مفتاح API إذا لزم الأمر"
                                        aria-describedby="modal-error" // Can share error description
                                     />
                                 </div>
                                 */}
                                 {/* --- End of Optional API Key Field --- */}

                                 <p id="modal-error" className="modal-error-message">{error || '\u00A0'}</p>

                                 <button type="submit" className="form-button" disabled={!username.trim()}>
                                      <i className={`fas ${canCreateDummy ? 'fa-plus' : 'fa-cog'}`} style={{ marginLeft: '8px' }}></i>
                                      {canCreateDummy ? ` إنشاء حساب ${platformName} وهمي` : ` إعداد حساب ${platformName}`}
                                  </button>
                             </form>
                         ) : (
                             // --- Success View (Only shown if canCreateDummy was true) ---
                             <div className="account-creation-success">
                                <h3><i className="fas fa-check-circle"></i> نجاح!</h3>
                                <p>تم إنشاء بيانات تسجيل دخول وهمية لحساب {platformName}. يمكنك استخدامها للتجربة. يرجى نسخها أو تسجيلها:</p>
                                <div className="credential-display">
                                     <span className="credential-text">{dummyEmail}</span>
                                     <button className={`copy-button ${emailCopied ? 'copied' : ''}`} onClick={() => handleCopy(dummyEmail, 'email')}
                                         aria-label="نسخ البريد الإلكتروني" disabled={emailCopied} type="button" >
                                        {emailCopied ? <><i className="fas fa-check"></i> تم النسخ</> : <><i className="far fa-copy"></i> نسخ</>}
                                     </button>
                                 </div>
                                 <div className="credential-display">
                                     <span className="credential-text">{dummyPassword}</span>
                                     <button className={`copy-button ${passwordCopied ? 'copied' : ''}`} onClick={() => handleCopy(dummyPassword, 'password')}
                                         aria-label="نسخ كلمة المرور" disabled={passwordCopied} type="button" >
                                        {passwordCopied ? <><i className="fas fa-check"></i> تم النسخ</> : <><i className="far fa-copy"></i> نسخ</>}
                                     </button>
                                 </div>
                                 {/* Error message specifically for copy failures */}
                                 <p id="modal-copy-error" className="modal-error-message" style={{textAlign: 'center', marginTop: '15px'}}>{error || '\u00A0'}</p>
                                <div className="modal-close-action">
                                     <button onClick={closeModal} className="form-button" type="button">
                                        <i className="fas fa-times" style={{marginLeft: '8px'}}></i> إغلاق
                                     </button>
                                </div>
                             </div>
                         )}
                     </div>
                </div>
            );
         }


        // --- Home Dashboard View ---
        function HomeDashboard({ userEmail, openSetupModal }) {
             const displayName = userEmail ? userEmail.split('@')[0] : 'المستخدم';
            return (
                <div className="main-content">
                    <div className="welcome-header">
                         <h1>مرحباً بك، {displayName}!</h1>
                         <p>لوحة تحكم حسابات التواصل الاجتماعي الخاصة بك في Haawa.</p>
                    </div>
                    <div className="dashboard-grid">
                        {/* Pass platform identifier */}
                        <SocialCardPro platform="facebook" iconClass="fa-facebook-f" onSetupAccount={openSetupModal} delay={0.1} />
                        <SocialCardPro platform="instagram" iconClass="fa-instagram" onSetupAccount={openSetupModal} delay={0.2} />
                        {/* Add more platforms here if needed */}
                    </div>
                </div>
            );
        }

        // --- Login View ---
        function LoginView({ onLoginSuccess, setLoginEmail }) {
            const [email, setEmail] = useState('');
            const [password, setPassword] = useState('');
            const [error, setError] = useState('');
            const emailInputRef = useRef(null);

             useEffect(() => { if(emailInputRef.current) { emailInputRef.current.focus(); } }, []);

            const handleLogin = (event) => {
                event.preventDefault();
                setError('');
                // --- Dummy Login Credentials ---
                // You might want to replace this with a real authentication call
                if (email.toLowerCase() === 'instagram@gmail.com' && password === 'Instagram@gmail.com') {
                    setLoginEmail(email); // Store email for display
                    onLoginSuccess(); // Trigger state change in App
                } else {
                    setError('بيانات الاعتماد غير صحيحة. يرجى المحاولة مرة أخرى.');
                     setPassword(''); // Clear password field on error
                     if(emailInputRef.current) { emailInputRef.current.focus(); } // Refocus email
                }
            };

            return (
                <div className="login-wrapper">
                    <div className="login-container">
                        <div className="login-logo">Haawa</div>
                        <h2 className="login-title">تسجيل الدخول إلى حسابك</h2>
                        <form onSubmit={handleLogin}>
                            <div className="form-group">
                                <label htmlFor="email">البريد الإلكتروني</label>
                                <input ref={emailInputRef} type="email" id="email" value={email} onChange={(e) => { setEmail(e.target.value); setError(''); }}
                                    placeholder="you@example.com" required aria-describedby="login-error" />
                            </div>
                            <div className="form-group">
                                <label htmlFor="password">كلمة المرور</label>
                                <input type="password" id="password" value={password} onChange={(e) => { setPassword(e.target.value); setError(''); }}
                                    placeholder="••••••••" required aria-describedby="login-error" />
                            </div>
                            <p id="login-error" className="error-message">{error || '\u00A0'}</p>
                            <button type="submit" className="form-button" disabled={!email || !password}>
                               <i className="fas fa-sign-in-alt"></i> تسجيل الدخول
                            </button>
                        </form>
                    </div>
                 </div>
            );
        }

        // --- Main App Component ---
        function App() {
            const [isLoggedIn, setIsLoggedIn] = useState(false);
            const [loggedInUserEmail, setLoggedInUserEmail] = useState(''); // Store logged in user's email
            const [currentView, setCurrentView] = useState('login'); // Start with login view
            const [isModalOpen, setIsModalOpen] = useState(false);
            const [modalPlatform, setModalPlatform] = useState(null); // Track which platform modal is for

            // --- Authentication Handlers ---
            const handleLoginSuccess = () => { setIsLoggedIn(true); setCurrentView('home'); };
            const handleLogout = () => {
                setIsLoggedIn(false);
                setLoggedInUserEmail('');
                setCurrentView('login');
                setIsModalOpen(false); // Ensure modal closes on logout
            };

            // --- Navigation ---
            const navigateTo = (view) => {
                if (view === 'login') {
                    handleLogout(); // Use logout handler for login navigation
                } else if (isLoggedIn && view === 'home') {
                    setCurrentView('home');
                }
                // Add other views if needed
            };

            // --- Modal Handlers ---
            const openSetupModal = (platform) => {
                setModalPlatform(platform);
                setIsModalOpen(true);
            };
            // Use useCallback to prevent unnecessary re-renders of the modal if passed as prop
            const closeSetupModal = useCallback(() => {
                setIsModalOpen(false);
                setModalPlatform(null); // Reset platform when closing
            }, []);

            // --- Account Setup Callback (Called from Modal) ---
            const handleAccountSetup = (platform, username, dummyEmail = null, dummyPassword = null, apiKey = null) => {
                // This is where you would typically interact with a backend API
                console.log(`Callback received for ${platform}:`);
                console.log(` -> Username: ${username}`);
                 if (dummyEmail) {
                     console.log(` -> Dummy Email: ${dummyEmail}`);
                 }
                 if (dummyPassword) {
                     console.log(` -> Dummy Password: ${dummyPassword}`);
                 }
                 if (apiKey) {
                     console.log(` -> API Key Provided: ${apiKey ? 'Yes' : 'No'}`); // Log if API key was entered
                 }
                 // In a real app: send this data to your server, update UI state, etc.

                 // Currently, we just log it. The modal closes itself if needed.
            };

            // --- Render Current View ---
            let viewComponent;
            if (!isLoggedIn) {
                // Pass login success handler and function to set email
                viewComponent = <LoginView onLoginSuccess={handleLoginSuccess} setLoginEmail={setLoggedInUserEmail} />;
            } else {
                // Pass user email and modal opener function
                viewComponent = <HomeDashboard userEmail={loggedInUserEmail} openSetupModal={openSetupModal} />;
            }

            return (
                <>
                   <Header navigateTo={navigateTo} logout={handleLogout} isLoggedIn={isLoggedIn} />
                   <main className="view-container">
                       {viewComponent}
                   </main>
                   {/* Conditionally render the modal */}
                   {isModalOpen && modalPlatform && (
                       <SetupAccountModal
                           platform={modalPlatform}
                           closeModal={closeSetupModal}
                           onAccountSetup={handleAccountSetup}
                       />
                   )}
                </>
            );
        }

        // Render App to the DOM
        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(<React.StrictMode><App /></React.StrictMode>);
    </script>

</body>
</html>
