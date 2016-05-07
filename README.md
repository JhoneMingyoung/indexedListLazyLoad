# indexedListLazyLoad
mui-indexedList and jquery-lazyLoad,
Tips1、 no placeholder,don't give use data:uri (placeholder);
Tips2、 change   "$container.on(settings.event, function() {return update();});"   to   " $("div").on(settings.event, function() {return update();});" to work with indexedList's container
