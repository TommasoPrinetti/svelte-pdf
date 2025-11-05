<script>
    import PdfViewer from '$lib/PdfViewer.svelte';
    import sampleLocal from '$lib/sample-local-pdf.pdf';
</script>

<PdfViewer
    url={sampleLocal}
    twoPage={true}
    showButtons={[ 'navigation', 'zoom', 'rotate', 'pageInfo', 'timeInfo', 'download', 'print', 'autoflip' ]}
    showBorder={true}
    showTopButton={true}
/>